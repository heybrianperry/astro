# Development Guidelines

## Project Structure & Module Organization

This repository contains Astro framework packages and tools.

## Build, Test, and Development Commands

Refer to package.json scripts for build and development commands.

## Coding Style & Naming Conventions

1. Use Prettier ^3.6.2 for code formatting in all source files
2. Use Node.js native modules (node:fs, node:path, node:url) for file system operations and path manipulation

## Testing Guidelines

1. Use Playwright 1.56.1 for end-to-end browser testing in all E2E test files

## Database & Authentication

1. Use Drizzle ORM ^0.42.0 for type-safe database operations in database integration packages
2. Use cookie library ^1.0.2 for parsing and serializing HTTP cookies in session management

## Framework Integration

1. Use Preact 10.27.1 as a lightweight React alternative for size-constrained scenarios