# Language-Specific Coding Standards

To ensure consistency across the repository, please follow these guidelines for each language.

## Testing and Code Templates

Each solution must include local test cases to verify the logic before submitting to the platform.

### Rust Template

- **File:** `problem_name.rs`
- **Run with:** `rustc --test problem_name.rs && ./problem_name`
- **Structure:** Include a `mod tests` at the bottom of the file.

### Python Template

- **File:** `problem_name.py`
- **Run with:** `python problem_name.py`
- **Structure:** Use `if __name__ == "__main__":` with `assert` statements.

### Julia Template

- **File:** `problem_name.jl`
- **Run with:** `julia problem_name.jl`
- **Structure:** Use the `Test` standard library and `@testset`.

## Starter Templates

To make it easier to start a new problem, we have provided boilerplate templates for each language. These include the required header and testing structure.

- [Rust Template](../templates/template.rs)
- [Python Template](../templates/template.py)
- [Julia Template](../templates/template.jl)
