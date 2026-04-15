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

We follow a simple commit message convention:

- `feat: add solution for [Problem Name]`
- `fix: correct logic in [Problem Name]`
- `docs: update contributing guidelines`
- `refactor: optimize time complexity for [Problem Name]`

## Code Style

We support solutions in **Rust, Python, and Julia**. Please ensure your code adheres to our language-specific standards.
**[Read the Language-Specific Rules here](./docs/language-rules.md)**

## ⚖️ License

By contributing to this repository, you agree that your contributions will be licensed under the **MIT License**.
