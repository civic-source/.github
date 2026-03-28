# Contributing to civic-source

Thank you for your interest in contributing. These guidelines apply to all repositories in the civic-source organization.

## Getting Started

1. Fork the repository
2. Create a feature branch (`feat/description` or `fix/description`)
3. Make your changes
4. Run tests: `pnpm test`
5. Run linting: `pnpm lint`
6. Run type check: `pnpm typecheck`
7. Submit a pull request

## Code Standards

- **Language:** TypeScript (strict mode, no `any`)
- **Testing:** Vitest — write tests alongside or before implementation
- **Formatting:** Prettier (auto-formatted on commit)
- **Commits:** Conventional commits (`feat:`, `fix:`, `chore:`, `docs:`, `test:`)

## What We Value

- **Correctness over cleverness.** Code should be easy to understand and verify.
- **Tests define behavior.** If it's not tested, it doesn't work.
- **Precise documentation.** State what something does. Don't exaggerate.

## Independence Disclaimer

This is an independent community project. It is not affiliated with, endorsed by, or associated with any government agency, employer, or official body. All contributions are made in a personal capacity.

## License

By contributing, you agree that your contributions will be licensed under the project's existing license (Apache 2.0 for code repositories, CC0 1.0 for data repositories).

## Reporting Issues

Use GitHub Issues in the relevant repository. Include:
- What you expected to happen
- What actually happened
- Steps to reproduce
- Relevant logs or error messages
