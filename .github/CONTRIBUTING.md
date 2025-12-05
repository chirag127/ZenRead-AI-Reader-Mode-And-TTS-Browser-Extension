# Contributing to ZenRead-AI-Content-Reader-Browser-Extension

We appreciate your interest in contributing to **ZenRead-AI-Content-Reader-Browser-Extension**! This guide outlines the essential steps and guidelines to ensure a smooth, efficient, and high-quality contribution process. Our philosophy is "Zero-Defect, High-Velocity, Future-Proof," and we expect all contributions to align with this standard.

## 1. Code of Conduct

By participating in this project, you are expected to uphold our [Code of Conduct](https://github.com/chirag127/ZenRead-AI-Content-Reader-Browser-Extension/blob/main/.github/CODE_OF_CONDUCT.md). Please treat everyone with respect and foster a positive, inclusive environment.

## 2. How Can I Contribute?

There are many ways to contribute, not just by writing code:

*   **Report Bugs:** Identify and report issues to help us improve stability and correctness.
*   **Suggest Enhancements:** Propose new features or improvements to existing ones.
*   **Improve Documentation:** Enhance our `README.md`, `AGENTS.md`, or other documentation.
*   **Submit Code:** Implement new features, fix bugs, or improve performance.
*   **Review Code:** Provide constructive feedback on Pull Requests.

## 3. Reporting Bugs

*   Before submitting a new bug report, please check existing issues to see if the problem has already been reported.
*   Use our dedicated [Bug Report Template](https://github.com/chirag127/ZenRead-AI-Content-Reader-Browser-Extension/blob/main/.github/ISSUE_TEMPLATE/bug_report.md) to ensure all necessary information is provided.
*   Clearly describe the steps to reproduce the bug, expected behavior, and actual behavior. Include screenshots or videos if helpful.
*   Specify your browser (Chrome, Firefox, Edge) and version, as well as the extension version.

## 4. Suggesting Enhancements

*   Before submitting an enhancement suggestion, please check existing issues for similar ideas.
*   Open a new issue and clearly describe your proposed feature or enhancement.
*   Explain *why* this enhancement is valuable and how it improves the user experience or project functionality.
*   Provide any mockups or examples if applicable.

## 5. Your First Code Contribution

If you're new to the project, consider looking for issues labeled `good first issue` or `help wanted`.

## 6. Setting Up Development Environment

This project is built using modern web technologies, focusing on a robust and scalable architecture.

### Prerequisites

*   **Node.js**: Latest LTS version (e.g., v20.x or higher)
*   **pnpm**: A fast, disk space efficient package manager. Install with `npm install -g pnpm`.
*   **Git**: For version control.

### Installation Steps

1.  **Fork the repository:** Click the "Fork" button at the top right of this page.
2.  **Clone your forked repository:**
    bash
    git clone https://github.com/your-username/ZenRead-AI-Content-Reader-Browser-Extension.git
    cd ZenRead-AI-Content-Reader-Browser-Extension
    
3.  **Install dependencies:**
    bash
    pnpm install
    
4.  **Start development server (for WXT extensions):**
    bash
    pnpm dev
    
    This will typically start a development server that rebuilds on changes and allows loading the extension into your browser for testing (e.g., via `chrome://extensions` -> Load unpacked).

## 7. Branching Strategy

We follow a `main` branch protected strategy. All contributions should be made via feature branches:

*   Create a new branch from `main`: `git checkout -b feature/your-feature-name` or `bugfix/issue-number`.
*   Keep your branch updated with `main`: `git pull origin main` regularly.
*   Once your work is complete, push your branch: `git push origin feature/your-feature-name`.
*   Open a Pull Request.

## 8. Pull Request Guidelines

*   **Atomic Commits:** Make small, focused commits that each address a single concern.
*   **Meaningful Messages:** Write clear, descriptive commit messages following Conventional Commits (e.g., `feat: add AI summarization`, `fix: resolve reader mode styling issue`).
*   **Tests:** Ensure all new features have comprehensive unit tests (`Vitest`) and, where applicable, end-to-end tests (`Playwright`). All existing tests must pass.
*   **Linting/Formatting:** Ensure your code adheres to our strict linting and formatting rules enforced by `Biome`. Run `pnpm run lint:fix` and `pnpm run format` before committing.
*   **Documentation:** Update any relevant documentation (`README.md`, comments) for new features or significant changes.
*   **Follow Template:** Use the [Pull Request Template](https://github.com/chirag127/ZenRead-AI-Content-Reader-Browser-Extension/blob/main/.github/PULL_REQUEST_TEMPLATE.md) provided.
*   **Link Issues:** Reference any related issues in your PR description (e.g., `Closes #123`).
*   **Review:** Be responsive to feedback during the review process. Address comments promptly.

## 9. Coding Standards

We adhere to the following principles and tools:

*   **Language:** TypeScript (Strict Mode) for type safety and maintainability.
*   **Frameworks:** WXT for browser extension development, Vite for bundling.
*   **Architecture:** Feature-Sliced Design (FSD) is encouraged to ensure clear separation of concerns, scalability, and testability. Organize code by feature slices, layers, and segments.
*   **Linting & Formatting:** `Biome` is used for ultra-fast and opinionated linting and formatting. Strict adherence is mandatory.
*   **Principles:** Adhere to SOLID, DRY (Don't Repeat Yourself), and YAGNI (You Aren't Gonna Need It) principles.
*   **Accessibility:** Prioritize accessibility (A11y) in all UI/UX development, given the nature of an assistive content reader.
*   **Privacy:** All features and data handling must be designed with a privacy-first mindset.

## 10. Testing

Robust testing is critical to our "Zero-Defect" philosophy.

*   **Unit Tests:** Written with `Vitest` for individual functions, components, and modules.
*   **End-to-End (E2E) Tests:** Implemented with `Playwright` to simulate user interactions and verify the full extension functionality across different browsers.
*   **Run Tests Locally:**
    bash
    pnpm test           # Run all tests
    pnpm test:unit      # Run Vitest unit tests
    pnpm test:e2e       # Run Playwright E2E tests
    

## 11. Security Vulnerabilities

If you discover a security vulnerability, please report it responsibly by following our [Security Policy](https://github.com/chirag127/ZenRead-AI-Content-Reader-Browser-Extension/blob/main/.github/SECURITY.md). Do not open a public issue. We appreciate your efforts to keep our project and users safe.

Thank you for contributing to ZenRead-AI-Content-Reader-Browser-Extension!