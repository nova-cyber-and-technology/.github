# Contributing to NOVA

Thank you for your interest in contributing to NOVA. We welcome contributions from developers, security researchers, designers, technical writers, and anyone who shares our goal of building secure and reliable technology.

Whether you're fixing a bug, improving documentation, or proposing a new feature, your contribution is appreciated.

---

## Before You Start

- Read the project documentation.
- Search existing Issues and Pull Requests to avoid duplicates.
- Open an Issue first if you're planning a significant change, so we can discuss the approach before you put time into it.
- Keep discussions respectful and constructive.
- Questions or ideas you'd rather talk through first are welcome on our [Discord](https://discord.gg/novacont).

---

## Ways to Contribute

- Fixing bugs
- Improving documentation
- Adding new features
- Improving performance
- Reporting security issues responsibly (see below)
- Improving tests
- Reviewing Pull Requests
- Suggesting improvements

---

## Setting Up Your Environment

1. Fork the repository and clone your fork locally.
2. Install dependencies as described in the project's README.
3. Make sure you can build the project and run its test suite before making changes, so you know your baseline is clean.

Each NOVA repository may have its own setup steps (Node version, Python version, environment variables, etc.); check that repository's README for specifics.

---

## Development Workflow

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test your changes locally, including the existing test suite.
5. Submit a Pull Request.

Please keep Pull Requests focused on a single change whenever possible; smaller PRs are easier to review and merge.

---

## Branch Naming

We recommend the following convention:

```
feature/add-wallet-support
bugfix/fix-login
docs/update-readme
refactor/api-cleanup
hotfix/critical-fix
```

---

## Commit Messages

Write clear, meaningful commit messages. Examples:

```
feat: add escrow expiration support
fix: resolve API authentication issue
docs: improve installation guide
refactor: simplify contract validation
```

Avoid vague messages such as `update`, `fix`, `changes`, `misc`.

---

## Coding Standards

Please follow the style already used in the project:

- Write clean, maintainable code.
- Keep functions focused and readable.
- Add comments only when they clarify something non-obvious.
- Prefer descriptive variable and function names.
- Remove unused code before submitting.

Consistency with the existing codebase matters more than personal preference.

---

## Smart Contract Changes

Contracts handle real user funds, so PRs touching `NovaCont` or `NovaCont Lite` contracts get extra scrutiny:

- Include or update relevant tests for any logic change.
- Explain the reasoning behind the change in the PR description, not just what changed.
- Expect a slower, more careful review than a typical frontend or docs PR. This isn't a reflection on the contribution, it's how we treat anything that touches funds.

---

## Documentation

If your change affects functionality, update the relevant documentation as part of the same PR. Keeping docs in sync with the code is part of the contribution, not a separate step.

---

## Security

If you discover a security vulnerability, **do not open a public Issue.**

Please follow our [Security Policy](./SECURITY.md) instead and report it privately.

---

## Pull Requests

Before submitting, make sure:

- Your code builds successfully.
- Existing tests still pass.
- Documentation has been updated where relevant.
- Your PR description clearly explains the purpose of the change and, for non-trivial changes, why you made it this way.

---

## Licensing

By submitting a contribution, you agree that it will be licensed under the same license as the repository you're contributing to. Check that repository's `LICENSE` file for details.

---

## Code of Conduct

By participating in this project, you agree to follow our Code of Conduct. Please help us maintain a respectful, inclusive, and collaborative community.

---

## Thank You

Every contribution, large or small, helps improve NOVA. Thank you for helping us build secure technology.

**NOVA Cyber & Technology**
