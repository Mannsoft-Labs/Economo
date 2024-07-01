# Contributing to 'Economo'

Thank you for your interest in contributing to Economo! Here are some guidelines to help you get started:

## Coding Standards

- **Indentation:** Use 2 spaces for indentation.
- **Line Length:** Limit all lines to a maximum of 80 characters.
- **Naming Convention:**
  - Use `camelCase` for variables and functions.
  - Use `PascalCase` for class names.
  - Use `UPPER_SNAKE_CASE` for constants.

- **Comments:**
  - Use `//` for single line comments.
  - Use `/* ... */` for multi-line comments.
  - Every function should have a comment describing its purpose and parameters.

- **Code structure:**
  - Place imports at the top of the file.
  - Keep functions small and focused. A function should do one and only one thing, and do it well.
  - Avoid deeply nested code.

## Commit Messages

- **Format:**
  - Use the present tense ("Add feature" not "Added feature").
  - Use the imperative mood ("Move cursor to..." not "Moves cursor to...").
  - Limit the first line to 72 characters or less.
  - Reference issues and pull requests liberally **before** the first line.

- Example: ticket EC#123 - add user auth module; module handles: user login, user registration, passw recovery



## Branching Strategy

- **Main Branch:** Contains production-ready code.
- **Development Branch:** Contains the latest features and bug fixes that are ready for testing.

## Pull Requests

- Ensure your PR is up to date with the latest changes in the development branch.
- Include a description of the changes and why they are being introduced.
- Link to any relevant issues.
- Request a review from at least one other team member.
- Ensure all tests pass before submitting the PR.

## Code Review Checklist

- Does the code follow the documented coding standards?
- Are all functions and classes well-documented?
- Is the code free of obvious bugs and errors?
- Are all unit tests and integration tests passing?
- Are there any performance concerns?
- Is the code modular and reusable?
- Is the code readable and maintainable?

