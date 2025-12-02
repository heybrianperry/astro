## Project Structure & Module Organization

The repository follows a monorepo structure. Refer to the project's existing directory layout for specific module organization.

## Build, Test, and Development Commands

Refer to the project's package.json and documentation for specific build, test, and development commands.

## Coding Style & Naming Conventions

1. Use Prettier ^3.6.2 for code formatting in all source files
2. Use Node.js native modules (node:fs, node:path, node:url) for file system operations and path manipulation
3. Use Drizzle ORM ^0.42.0 for type-safe database operations in database integration packages
4. Use Preact 10.27.1 as a lightweight React alternative for size-constrained scenarios

## Testing Guidelines

1. Use Playwright 1.56.1 for end-to-end browser testing in all E2E test files

## Commit & Pull Request Guidelines

Follow the project's existing commit and pull request conventions.

## Security & Configuration Tips

1. Use cookie library ^1.0.2 for parsing and serializing HTTP cookies in session management