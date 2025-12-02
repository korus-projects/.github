# Contributing to Korus Framework

Thank you for your interest in contributing to the **Korus Framework**!  
We welcome contributions from the community and appreciate your time and effort.

There are many ways to contribute to Korus:
- Reporting bugs  
- Requesting features  
- Improving documentation  
- Submitting pull requests  
- Improving performance  
- Creating modules or integrations  

This document explains the process and rules to ensure high-quality contributions.

---

## 🚀 Before You Start

1. **Read the README** of the repository you want to contribute to.  
2. **Check existing issues/PRs** to avoid duplicates.  
3. Ensure your idea aligns with the long-term vision of Korus.

---

## ⚖️ Contributor License Agreement (CLA)

All external contributors **must sign the CLA** before we can accept a PR.

The CLA bot will automatically comment on your pull request with a link to sign.

Your PR will not be merged until:
- ✔ CLA is signed  
- ✔ All checks pass  

This ensures legal safety for both contributors and Korus.

---

## 📝 How to Report Bugs

If you find a bug:

1. Search existing **Issues** to avoid duplicates.  
2. If not found, create a new bug report using the template.  
3. Include:
   - Steps to reproduce  
   - Expected behavior  
   - Actual behavior  
   - Environment details  
   - Code snippets if relevant  

Bug reports with clear steps get resolved faster.

---

## 💡 Requesting New Features

We welcome feature suggestions!

Please follow these guidelines:

- Check if the feature has already been requested.  
- Clearly explain *why* the feature is needed.  
- Provide examples or use cases.  
- Mention alternative solutions if any.  

Large features may require discussion before implementation.

---

## 🧩 Submitting Pull Requests

### ✔ 1. Fork the repository  
Click the **Fork** button.

### ✔ 2. Create a new branch  
Use this format:

```

feature/description
fix/issue-id
improvement/topic

```

Example:

```

feature/config-system
fix/412

```

### ✔ 3. Write clean, consistent code  
Follow the Korus coding standards:

- Use meaningful commit messages  
- Format code using standard Java conventions  
- Add Javadoc for public APIs  
- Add tests where appropriate  
- Ensure code builds without warnings  

### ✔ 4. Work in small commits  
Avoid large, complex commits.  
Structure them logically.

### ✔ 5. Ensure all tests pass  
Run:

```

mvn clean verify       (if using Maven)
gradle build           (if using Gradle)

```

### ✔ 6. Submit your pull request  
Your PR *must include*:

- Description of changes  
- Reference to Issues (e.g., `Closes #123`)  
- Any breaking changes clearly documented  

### ✔ 7. Sign the CLA  
The CLA bot will remind you if needed.

---

## 🧪 Code Style & Standards

All code must follow:

- Standard Java formatting  
- Idiomatic design patterns  
- Clear API naming  
- Proper package structure  
- Javadoc for public classes/methods  

If contributing to multiple modules, follow each module’s structure.

---

## 📘 Documentation Contributions

We love documentation improvements!

- Fix typos  
- Improve examples  
- Add tutorials  
- Enhance explanations  

Documentation PRs do **not** require tests.

---

## 🔍 Commit Message Guidelines

Use clear messages:

```

feat: add new config parser
fix: resolve null pointer in logger
docs: improve getting started guide
refactor: cleanup utils
test: add unit tests for http client
perf: optimize reflection caching

```

---

## 🏗 Project Structure (General)

Korus Framework repositories may include:

```

core/
modules/
extensions/
api/
docs/
tests/
examples/

```

Follow the structure and place files accordingly.

---

## 🤝 Community Conduct

All contributors must follow the **Code of Conduct**.  
Respectful communication is required.

---

## ❤️ Thank You

Your contributions help Korus grow into a powerful, community-driven framework.  
We appreciate your support and effort.

Happy coding!
