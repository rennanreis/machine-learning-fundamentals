
# Contribution Guidelines

Thank you for your interest in contributing to the **Machine Learning Fundamentals** project! This document outlines the best practices for making contributions, including commits, branching, and versioning.

## Commit Best Practices
1. **Commit Messages**:
   - Use clear and concise messages.
   - Follow the format:
     ```
     <type>: <short description>
     ```
     - **`type`**: Specify the type of change (e.g., `feat`, `fix`, `docs`, `refactor`).
     - **`description`**: A brief description of the change.

   - Examples:
     - `feat: Add preprocessing script for data cleaning`
     - `fix: Resolve issue with notebook loading`

2. **Commit Size**:
   - Make commits small and focused on a single change.
   - Avoid bundling multiple unrelated changes in one commit.

3. **Use Conventional Commits**:
   - Types:
     - `feat`: A new feature.
     - `fix`: A bug fix.
     - `docs`: Documentation updates.
     - `style`: Code style changes (e.g., formatting).
     - `refactor`: Code restructuring without changing functionality.
     - `test`: Adding or modifying tests.
     - `chore`: Maintenance tasks (e.g., updating dependencies).

## Branching Strategy
1. **Branch Naming**:
   - Use descriptive branch names:
     ```
     <type>/<short-description>
     ```
     - Examples:
       - `feature/add-iris-dataset`
       - `bugfix/notebook-import-issue`

2. **Main Branch Rules**:
   - The `main` branch should always be production-ready.
   - Ensure all changes are reviewed and tested before merging into `main`.

3. **Pull Requests**:
   - Submit pull requests for any changes to the `main` branch.
   - Include a clear description of the changes in the pull request.

## Versioning
- Use **Semantic Versioning (SemVer)**:
  - Format: `MAJOR.MINOR.PATCH`
  - Examples:
    - `1.0.0`: First stable release.
    - `1.1.0`: New features added, backward-compatible.
    - `1.1.1`: Bug fixes, backward-compatible.
