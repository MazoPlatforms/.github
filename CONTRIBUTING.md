# Contributing to Mazo Platforms

Thank you for your interest in contributing to Mazo Platforms, Inc.! We welcome contributions from developer communities of all skill levels. Whether you are fixing a bug, improving documentation, or proposing new feature modules, your help is appreciated.

Please take a moment to review this document to ensure a smooth, efficient contribution process.

---

## 📜 Code of Conduct

By participating in our projects, you agree to maintain a respectful, inclusive, and professional environment for everyone. Please treat all contributors with kindness and respect.

---

## 🛠️ How Can You Contribute?

### 1. Reporting Bugs
Before creating a bug report, please check existing repository issues to see if the bug has already been reported. If not, open a new issue using our **Bug Report Template** and include:
* A clear, descriptive title.
* Step-by-step instructions to reproduce the issue.
* Expected vs. actual behavior.
* Relevant environment details (Node version, OS, browser, package version).

### 2. Requesting Features
We love hearing ideas for new tools, components, and enhancements! Please submit feature requests using our **Feature Request Template** detailing:
* The problem or limitation your feature solves.
* A clear description of the proposed solution or feature capability.
* Alternatives considered.

### 3. Submitting Pull Requests (PRs)
* **Check for existing issues:** Make sure your PR references an existing issue or feature request.
* **Keep PRs focused:** Submit smaller, modular PRs over massive overhauls whenever possible.
* **Write clear commit messages:** Use clean, descriptive commit messages describing *what* changed and *why*.

---

## 💻 Development Workflow & Code Standards

### Branching Strategy
We follow a standard Git Feature Branch workflow:
1. Fork the target repository.
2. Create a feature or bugfix branch from `main`:
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bugfix-name```

 * Commit your changes locally.
 * Push your branch to your fork and submit a Pull Request to main.
Code Style Guidelines
 * TypeScript & JavaScript:
   * Use TypeScript for modern web components and packages wherever applicable.
   * Follow modern ES6+ practices and maintain strict typing (noImplicitAny).
   * Ensure linting and formatting pass (e.g., ESLint, Prettier).
 * Kotlin & Mobile:
   * Adhere to official Android/Kotlin coding conventions.
   * Keep Jetpack Compose state management clean, unidirectional, and modular.
 * Documentation:
   * Update inline docstrings/JSDoc comments for any core exported functions or components.
   * Update repository README files if your changes alter build, installation, or configuration instructions.
🧪 Testing & Validation
Before submitting your PR, make sure to verify:
 * The project builds cleanly without errors or warnings.
 * Existing test suites pass successfully.
 * You have added new unit or integration tests covering your changes where relevant.
# Example check command
npm run lint && npm run test

🚀 Pull Request Checklist
When creating a PR, ensure your submission fulfills the following:
 * [ ] Linked to the relevant issue (e.g., Closes #12).
 * [ ] Code follows project style guidelines and passes local linting.
 * [ ] Tests have been added/updated and pass locally.
 * [ ] Documentation has been updated accordingly.
Thank you for helping build high-performance platforms with Mazo Platforms!

