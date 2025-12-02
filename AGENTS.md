# Development Guidelines

This document contains development guidelines and policies for the Astro repository.

## Project Structure & Module Organization

The repository follows a monorepo structure. Organize code by feature and maintain clear module boundaries.

## Build, Test, and Development Commands

Use standard npm/pnpm commands for development tasks:
- Build commands for compilation
- Test commands for running test suites
- Development commands for local iteration

## Coding Style & Naming Conventions

1. Use Prettier ^3.6.2 for code formatting in all source files
2. Follow consistent naming conventions across the codebase
3. Use descriptive variable and function names

## Testing Guidelines

1. Use Playwright 1.56.1 for end-to-end browser testing in all E2E test files
2. Write tests that cover critical user paths
3. Maintain test reliability and determinism

## Technology & Framework Guidelines

### Database Access
1. Use Drizzle ORM ^0.42.0 for type-safe database operations in database integration packages

### Authentication
1. Use cookie library ^1.0.2 for parsing and serializing HTTP cookies in session management

### Node.js APIs
1. Use Node.js native modules (node:fs, node:path, node:url) for file system operations and path manipulation

### Multi-Framework Support
1. Use Preact 10.27.1 as a lightweight React alternative for size-constrained scenarios

## Commit & Pull Request Guidelines

1. Write clear, descriptive commit messages
2. Keep commits focused and atomic
3. Reference relevant issues in commit messages
4. Ensure tests pass before submitting pull requests

## Security & Configuration Tips

1. Use secure session management practices with appropriate cookie settings
2. Follow security best practices for authentication flows
3. Keep dependencies up to date for security patches