# Contributing to Fundamics LMS Backend

Guidelines and conventions for contributing to the LMS backend codebase.

## Branching Strategy

- `main`: Production-ready, stable branch.
- `dev` / `develop`: Integration branch for ongoing development.
- Feature branches: `feat/<feature-name>`
- Bugfix branches: `fix/<bug-name>`
- Chore/Refactor branches: `chore/<description>` or `refactor/<description>`

## Commit Message Conventions

Follow the Conventional Commits format:
```
<type>(<optional scope>): <description>

[optional body]

[optional footer(s)]
```

Common types:
- `feat`: A new feature or API endpoint
- `fix`: A bug fix
- `docs`: Documentation updates
- `refactor`: Code change that neither fixes a bug nor adds a feature
- `test`: Adding or correcting tests
- `chore`: Build tasks, dependency updates, configuration changes

## Pull Request Process

1. Ensure existing and new tests pass locally.
2. Adhere to code style and linting standards.
3. Update relevant API specifications or architecture docs in `docs/` when introducing changes.
4. Keep pull requests focused on a single topic or feature.
