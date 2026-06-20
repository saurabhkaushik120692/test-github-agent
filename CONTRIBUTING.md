# Contributing Guidelines

Thank you for considering contributing to **Your Project Name**! We appreciate your help in making this project better. Please follow these guidelines to streamline the contribution process.

## How to Contribute

1. **Fork the repository** and clone your fork locally.
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```
2. **Create a new branch** for your work.
   ```bash
   git checkout -b my-feature
   ```
3. **Make your changes**. Ensure that you adhere to the coding style (see below).
4. **Write tests** for new functionality or bug fixes.
5. **Run the test suite** to confirm everything passes.
   ```bash
   pytest
   ```
6. **Commit your changes** with a clear, descriptive commit message.
   ```bash
   git commit -m "Add ..." 
   ```
7. **Push to your fork** and open a Pull Request (PR) against the `main` branch.
   ```bash
   git push origin my-feature
   ```

## Code Style

- Format code with **black**.
- Lint with **flake8** (line length ≤ 88 characters).
- Include docstrings for all public functions and classes.
- Update documentation when public APIs change.

## Pull Request Process

- Ensure all CI checks pass (tests, linting, type checking).
- Provide a clear description of what the PR does.
- Reference any related issues using `#issue_number`.
- Be responsive to reviewer feedback and make any requested changes.

## Reporting Issues

If you encounter a bug or have a feature request, please open an issue with:
- A descriptive title.
- Steps to reproduce (for bugs).
- Expected vs. actual behavior.
- Any relevant logs or screenshots.

## License

By contributing, you agree that your contributions will be licensed under the project's MIT License.
