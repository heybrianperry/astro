# Development Guidelines

This document outlines the development guidelines and policies for the Astro repository.

## Project Structure & Module Organization

The repository follows a monorepo structure with packages organized by functionality.

## Build, Test, and Development Commands

Refer to the repository's package.json and individual package documentation for build, test, and development commands.

## Coding Style & Naming Conventions

1. Use Drizzle ORM ^0.42.0 for type-safe database operations in database integration packages
2. Use Preact 10.27.1 as a lightweight React alternative for size-constrained scenarios
3. Follow TypeScript best practices for type safety
4. Use descriptive variable and function names

## Testing Guidelines

1. Write tests for new features and bug fixes
2. Ensure tests pass before submitting pull requests
3. Aim for meaningful test coverage of critical paths

## Commit & Pull Request Guidelines

1. Write clear, descriptive commit messages
2. Reference relevant issues in commits and PRs
3. Keep pull requests focused and reviewable
4. Ensure CI checks pass before requesting review

## Security & Configuration Tips

1. Never commit sensitive credentials or API keys
2. Use environment variables for configuration
3. Follow security best practices for dependencies