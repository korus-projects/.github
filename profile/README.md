<!-- Header section -->

<h1 style="font-size: 32px; font-weight: bold; margin: 0; padding: 0;">
  Korus Framework
</h1>

Lightweight JVM framework where Java Compiles Into Power

<!-- Badges (all left-aligned) -->
<p>
  <img src="https://img.shields.io/badge/Java-17%2B-007396?logo=java&logoColor=white" alt="Java 17+">
  <img src="https://img.shields.io/badge/Build-Maven-C71A36?logo=apache-maven&logoColor=white" alt="Maven">
</p>

## Introduction

Korus Framework is a build-time dependency injection framework for ultra-fast Java applications on the JVM.

It removes reflection, classpath scanning and runtime dependency wiring, while preserving a clean, annotation-driven experience that will feel familiar to Spring Boot users.

Korus focuses on moving framework work to compile time. The annotation processor generates routing, dependency graphs, configuration metadata and validation logic during compilation. The runtime layer then stays very small and predictable.

Website: [https://korus-projects.github.io/](https://korus-projects.github.io/)

Status: Korus is under active development. APIs may evolve as the project matures.

## What is Korus?

Korus is a modern Java framework built around annotation processing, compile-time bean creation and a lightweight runtime.

All routing, dependency wiring, configuration metadata and validation logic are generated during compilation instead of at runtime. This enables:

- Zero reflection  
- Zero classpath scanning  
- Zero dynamic proxies  
- Fast startup characteristics  
- Low memory footprint  
- Strict compile-time safety  

Korus aims to provide the ergonomics of Spring Boot with the performance-oriented design of build-time frameworks.

## Build-Time Dependency Injection

Korus performs dependency injection at build time:

- Constructor and method injection are written into generated classes  
- Bean initialization order is determined deterministically during compilation  
- Circular dependencies can be detected at compile time  
- No runtime proxies or reflection are required for dependency wiring  

## Documentation

For guides, reference documentation and examples, visit:

[https://korus-projects.github.io/](https://korus-projects.github.io/)

## Acknowledgements

Korus Framework is shaped by the evolution of the JVM ecosystem.  
Its design philosophy is informed by the work of established frameworks such as **Spring Boot**, **Micronaut**, and **Quarkus**, each of which has made significant contributions to modern Java application development.

Their ecosystems and ideas have helped inspire the approach Korus takes toward build-time processing and developer experience.
