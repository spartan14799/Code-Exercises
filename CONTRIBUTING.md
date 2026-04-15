# Contributing to this project

First off, thank you for considering contributing! To maintain a clean and professional repository, please follow these guidelines when adding new solutions or improving existing ones.

## Getting Started

1. **Pick an Issue:** Check the [Issues] tab to see which problems are currently being worked on. If you want to solve a new one, create an issue first and assign it to yourself.
2. **Sync your local repository:** Always pull the latest changes from `main` before starting a new task.

## Branching Strategy

We use a feature-branch workflow. **Do not commit directly to the `main` branch.**

- **Branch naming convention:**
  - `solve/platform-problem-name`
  - `refactor/problem-name` (for optimizing existing code)
  - `docs/update-readme` (for documentation changes)

## Workflow & Pull Requests

1. **Create a branch** from `main`.
2. **Solve the problem** in the appropriate directory.
3. **Write clean code:** Use descriptive variable names and follow the language-specific style guide 
4. **Push your branch** and open a **Pull Request (PR)**.
5. **Code Review:** Every PR must be reviewed and approved by at least one other maintainer before merging.
6. **Merge:** Once approved and all tests pass, the branch can be merged into `main`.

## Repository Structure

Please organize your files as follows:

- `PlatformName/Difficulty/ProblemName.ext`
- Example: `LeetCode/Medium/3Sum.rs`

## Commit Messages

We follow the Conventional Commits standard. Our automated bot will reject any Pull Request whose commit messages do not start with one of the following prefixes:

- **feat:** A new solution or functionality (e.g., feat: add two sum in rust).
- **fix:** A bug fix in the code (e.g., fix: handle empty input in binary search).
- **refactor:** Code changes that neither fix a bug nor add a feature (e.g., refactor: optimize space complexity).
- **test:** Adding missing tests or correcting existing ones (e.g., test: add edge cases for sorting).
- **docs:** Documentation only changes (e.g., docs: update setup guide).
- **chore**: Maintenance tasks, dependencies, or tool configuration (e.g., chore: update github actions).
  
## Code Style

We support solutions in **Rust, Python, and Julia**. Please ensure your code adheres to our language-specific standards.
**[Read the Language-Specific Rules here](./docs/language-rules.md)**

## ⚖️ License

By contributing to this repository, you agree that your contributions will be licensed under the **MIT License**.
