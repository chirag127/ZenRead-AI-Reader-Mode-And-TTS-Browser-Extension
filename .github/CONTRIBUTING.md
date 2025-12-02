# Contributing to ZenRead-AI-Powered-Distraction-Free-Reader-Browser-Extension

Welcome! We are thrilled you're considering contributing to **ZenRead**, an advanced AI-powered browser extension designed for distraction-free reading. Your contributions help us maintain a high-quality, privacy-focused, and feature-rich tool for the community.

Please take a moment to review this document to understand our development process and guidelines.

## Table of Contents
- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Your First Code Contribution](#your-first-code-contribution)
  - [Pull Request Guidelines](#pull-request-guidelines)
- [Development Setup](#development-setup)
  - [Prerequisites](#prerequisites)
  - [Cloning the Repository](#cloning-the-repository)
  - [Installing Dependencies](#installing-dependencies)
  - [Running the Extension](#running-the-extension)
  - [Testing](#testing)
  - [Linting and Formatting](#linting-and-formatting)
- [Commit Message Guidelines](#commit-message-guidelines)
- [Security Vulnerabilities](#security-vulnerabilities)
- [License](#license)

---

## Code of Conduct

This project and everyone participating in it is governed by the [ZenRead Code of Conduct](https://github.com/chirag127/ZenRead-AI-Powered-Distraction-Free-Reader-Browser-Extension/blob/main/.github/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

If you find a bug, please help us by submitting an issue to our [GitHub Issues](https://github.com/chirag127/ZenRead-AI-Powered-Distraction-Free-Reader-Browser-Extension/issues). Before opening a new issue, please:
1.  **Check existing issues** to see if the bug has already been reported.
2.  Use the dedicated [bug report template](https://github.com/chirag127/ZenRead-AI-Powered-Distraction-Free-Reader-Browser-Extension/issues/new?assignees=&labels=bug&projects=&template=bug_report.md) and fill out all required information.
3.  Provide clear, concise steps to reproduce the bug.

### Suggesting Enhancements

We welcome suggestions for new features or improvements!
1.  **Check existing issues** to see if your suggestion has already been discussed.
2.  Open a new issue in our [GitHub Issues](https://github.com/chirag127/ZenRead-AI-Powered-Distraction-Free-Reader-Browser-Extension/issues).
3.  Clearly describe the enhancement, including its potential benefits and use cases.

### Your First Code Contribution

If you're new to the project, consider starting with issues labeled `good first issue` or `help wanted`. These are typically simpler and great for familiarizing yourself with the codebase.

### Pull Request Guidelines

1.  **Fork** the repository on GitHub.
2.  **Clone** your forked repository to your local machine.
3.  **Create a new branch** for your feature or bug fix: `git checkout -b feature/your-feature-name` or `git checkout -b bugfix/issue-number`.
4.  **Implement your changes**, following our [Development Setup](#development-setup) guidelines for linting and testing.
5.  **Write clear, concise commit messages** (see [Commit Message Guidelines](#commit-message-guidelines)).
6.  **Push your branch** to your forked repository.
7.  **Open a Pull Request** against the `main` branch of the original repository.
8.  **Fill out the Pull Request template** completely and include references to any related issues (e.g., `Fixes #123`, `Closes #456`).
9.  **Respond to feedback** from maintainers and reviewers.

## Development Setup

To get your development environment ready:

### Prerequisites

*   Node.js (LTS recommended)
*   npm or yarn (or pnpm)

### Cloning the Repository

bash
git clone https://github.com/chirag127/ZenRead-AI-Powered-Distraction-Free-Reader-Browser-Extension.git
cd ZenRead-AI-Powered-Distraction-Free-Reader-Browser-Extension


### Installing Dependencies

bash
# Using npm
npm install

# Or using yarn
yarn install

# Or using pnpm
pnpm install


### Running the Extension (Development Mode)

ZenRead is a browser extension. To run it in development mode:

bash
# Build for development (e.g., using Vite/WXT)
npm run dev

Then, load the generated `dist` or `build` directory as an unpacked extension in your browser (Chrome, Firefox, etc.). Consult the specific project documentation for detailed instructions on loading your extension.

### Testing

We use **Vitest** for unit and integration testing. Ensure all new features and bug fixes have adequate test coverage.

bash
# Run all tests
npm test

# Run tests in watch mode
npm run test:watch


### Linting and Formatting

We enforce strict code quality using **Biome** for linting and formatting to ensure consistency across the codebase.

bash
# Run linting and formatting checks
npm run lint
npm run format

# Automatically fix linting and formatting issues
npm run lint:fix
npm run format:fix


## Commit Message Guidelines

We follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification. This helps us generate changelogs and understand the nature of changes.

Examples:
*   `feat: add text-to-speech option`
*   `fix(parser): prevent infinite loop on malformed HTML`
*   `docs: update contributing guidelines`
*   `refactor: restructure Gemini API integration`
*   `chore: update dependencies`

## Security Vulnerabilities

We take security seriously. If you discover a security vulnerability, please report it responsibly by following our [Security Policy](https://github.com/chirag127/ZenRead-AI-Powered-Distraction-Free-Reader-Browser-Extension/blob/main/.github/SECURITY.md).

## License

By contributing to ZenRead, you agree that your contributions will be licensed under its [CC BY-NC 4.0 License](https://github.com/chirag127/ZenRead-AI-Powered-Distraction-Free-Reader-Browser-Extension/blob/main/LICENSE).