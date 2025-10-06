# Contributing to Git Ustasi

Thank you for your interest in contributing to Git Ustasi! This document provides guidelines for contributing to this open-source project.

## How to Contribute

### 1. Fork the Repository

1. Fork the repository on GitHub
2. Clone your fork locally:
   ```bash
   git clone https://github.com/your-username/git-ustasi.git
   cd git-ustasi
   ```

### 2. Set Up Development Environment

1. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

2. Run the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) to view the application

### 3. Create a Branch

Create a new branch for your feature or bug fix:

```bash
git checkout -b feature/your-feature-name
# or
git checkout -b fix/your-bug-fix
```

### 4. Make Your Changes

- Follow the existing code style and conventions
- Write clear, descriptive commit messages
- Test your changes thoroughly
- Ensure the application builds successfully

### 5. Commit Your Changes

```bash
git add .
git commit -m "Add: descriptive commit message"
```

### 6. Push and Create a Pull Request

1. Push your changes to your fork:

   ```bash
   git push origin your-branch-name
   ```

2. Create a Pull Request on GitHub with:
   - A clear title and description
   - Reference to any related issues
   - Screenshots (if applicable)

## Development Guidelines

### Code Style

- Use TypeScript for all new code
- Follow the existing naming conventions
- Use Tailwind CSS for styling
- Maintain responsive design principles
- Write meaningful comments for complex logic

### File Structure

- Keep components in the `components/` directory
- Use the `app/` directory for pages (Next.js 13+ App Router)
- Place utilities in the `lib/` directory
- Store static assets in the `public/` directory

### Commit Message Format

Use clear, descriptive commit messages:

- `Add: new feature description`
- `Fix: bug description`
- `Update: change description`
- `Remove: removal description`
- `Refactor: refactoring description`

## Types of Contributions

### Bug Reports

When reporting bugs, please include:

- Steps to reproduce the issue
- Expected behavior
- Actual behavior
- Screenshots (if applicable)
- Browser and OS information

### Feature Requests

For new features, please:

- Describe the feature clearly
- Explain why it would be useful
- Provide examples of how it would work
- Consider the impact on existing functionality

### Documentation

Help improve documentation by:

- Fixing typos and grammatical errors
- Adding missing information
- Improving clarity and structure
- Translating content to other languages

## Code Review Process

1. All contributions require review
2. Maintainers will review your code
3. Address feedback and make requested changes
4. Once approved, your changes will be merged

## Organization Repository

This project is also maintained by [iTechUz](https://github.com/iTechUz) organization:
**[https://github.com/iTechUz/gitustasi](https://github.com/iTechUz/gitustasi)**

## Questions?

If you have questions about contributing, please:

- Open an issue on GitHub
- Check existing issues and discussions
- Reach out to the maintainers
- Contact me on Telegram: [@shoxjahon_dev](https://t.me/shoxjahon_dev)

Thank you for contributing to Git Ustasi! 🚀
