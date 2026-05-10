# Contributing Guidelines

Thank you for your interest in contributing! We welcome contributions of all kinds.

## How to Contribute

### Reporting Bugs

1. Check the [existing issues](https://github.com/Pitt-Lee/my-opensource-project/issues) to avoid duplicates
2. Use the [Bug Report template](https://github.com/Pitt-Lee/my-opensource-project/issues/new?template=bug_report.yml)
3. Include steps to reproduce, expected behavior, and screenshots if applicable

### Suggesting Features

1. Use the [Feature Request template](https://github.com/Pitt-Lee/my-opensource-project/issues/new?template=feature_request.yml)
2. Describe the problem you're trying to solve
3. Explain your proposed solution

### Pull Requests

1. **Fork** the repository
2. **Create** a new branch from `main`:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make** your changes
4. **Test** your changes thoroughly
5. **Commit** with clear, descriptive messages:
   ```bash
   git commit -m "feat: add new feature description"
   ```
6. **Push** to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Open** a Pull Request against the `main` branch

### Commit Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` — New feature
- `fix:` — Bug fix
- `docs:` — Documentation changes
- `style:` — Code style changes (formatting, etc.)
- `refactor:` — Code refactoring
- `test:` — Adding or updating tests
- `chore:` — Maintenance tasks

### Code Style

- Follow the existing code style in the project
- Run linting before submitting: `npm run lint`
- Ensure all tests pass: `npm test`

## Development Setup

```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/my-opensource-project.git
cd my-opensource-project

# Install dependencies
npm install

# Start dev server
npm run dev
```

## Code of Conduct

Please read our [Code of Conduct](./CODE_OF_CONDUCT.md) before contributing.

## Questions?

Feel free to open an [issue](https://github.com/Pitt-Lee/my-opensource-project/issues) for any questions.
