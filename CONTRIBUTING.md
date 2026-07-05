# Contributing to Simple Interest Calculator

All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome.

Thank you for considering contributing to the Simple Interest Calculator project! We welcome contributions from developers of all skill levels. By participating in this project, you agree to abide by our [Code of Conduct](file:///c:/Users/vince/OneDrive/Documents/githubProject/CODE_OF_CONDUCT.md).


## How to Contribute

### 1. Reporting Bugs
If you find a bug or issue with the calculator script:
* Check the existing issues to ensure it hasn't already been reported.
* Open a new issue with a clear title and detailed description of the unexpected behavior.
* Include steps to reproduce the issue and your operating system / shell environment details.

### 2. Suggesting Enhancements
We love new ideas! To suggest a feature:
* Open an enhancement issue describing the proposed functionality and why it would be beneficial.
* Provide examples of how the feature would work from a user's perspective.

### 3. Submitting Pull Requests (PRs)
To contribute code or documentation changes:

1. **Fork the Repository:** Create a fork of this repository to your personal GitHub account.
2. **Clone your Fork:**
   ```bash
   git clone https://github.com/<your-username>/<repository-name>.git
   cd <repository-name>
   ```
3. **Create a Feature Branch:** Always create a descriptive branch for your work:
   ```bash
   git checkout -b feature/add-new-calculation
   # OR for bug fixes:
   git checkout -b bugfix/fix-division-error
   ```
4. **Make your Changes:** Edit code or documentation cleanly. Ensure shell scripts remain POSIX or Bash compliant.
5. **Test your Changes:** Run `./simple-interest.sh` locally to verify that your changes work as expected without errors.
6. **Commit your Changes:** Write clear, concise commit messages explaining the purpose of your commit:
   ```bash
   git commit -m "Add input validation for non-negative interest rates"
   ```
7. **Push to your Fork:**
   ```bash
   git push origin feature/add-new-calculation
   ```
8. **Open a Pull Request:** Go to the original repository on GitHub and open a Pull Request from your feature branch. Provide a brief summary of the changes in the PR description.

## Coding Style Guidelines
* Write clean, self-documenting Bash code.
* Use meaningful variable names (e.g., `principal`, `rate`, `time`).
* Include comments for complex logic or arithmetic operations.
* Ensure all scripts start with a standard shebang: `#!/bin/bash`.

Thank you for helping improve this open-source project!
