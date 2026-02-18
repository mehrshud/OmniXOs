# Contributing to OmniXOs
==========================

Thank you for considering contributing to OmniXOs! We appreciate your interest in our project and look forward to your contributions. This guide outlines the steps to contribute to OmniXOs, including how to fork the repository, create branches, and submit pull requests.

## Fork Guide
-------------

1. **Fork the repository**: Go to the [OmniXOs repository](https://github.com/omnixos/omnixos) and click the "Fork" button in the top-right corner.
2. **Clone the forked repository**: Run `git clone https://github.com/your-username/omnixos.git` to clone the forked repository to your local machine.
3. **Configure the upstream repository**: Run `git remote add upstream https://github.com/omnixos/omnixos.git` to configure the upstream repository.
4. **Verify the remotes**: Run `git remote -v` to verify that the remotes are set up correctly.

## Branch Naming
----------------

* **Feature branches**: Use the format `feature/your-feature-name` (e.g., `feature/new-login-system`).
* **Bug fix branches**: Use the format `fix/your-bug-fix-name` (e.g., `fix/login-issue`).
* **Release branches**: Use the format `release/your-release-name` (e.g., `release/v1.2.3`).
* **Hotfix branches**: Use the format `hotfix/your-hotfix-name` (e.g., `hotfix/security-patch`).

## Conventional Commits
----------------------

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification for commit messages. This ensures that our commit history is consistent and easily searchable. Please use the following format for your commit messages:

`type(scope): brief description`

Where:

* **type**: One of `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`, or `revert`.
* **scope**: Optional scope of the commit (e.g., `login-system`, `api`, etc.).
* **brief description**: Brief description of the commit.

Example: `feat(login-system): add new login feature`

## PR Checklist
----------------

Before submitting a pull request, please ensure that you have:

* **Forked the repository** and **cloned the forked repository** to your local machine.
* **Configured the upstream repository** and **verified the remotes**.
* **Created a new branch** for your feature or bug fix using the branch naming conventions.
* **Committed your changes** using conventional commit messages.
* **Pushed your changes** to your forked repository.
* **Submitted a pull request** to the main repository.
* **Filled out the PR template** completely and accurately.
* **Included any relevant screenshots or logs** to demonstrate the changes.
* **Tested your changes** thoroughly to ensure they do not introduce any bugs or regressions.

Thank you for taking the time to contribute to OmniXOs! We look forward to reviewing your pull requests.