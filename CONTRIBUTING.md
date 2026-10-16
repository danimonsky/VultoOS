# Contributing to Vulto OS

First of all, thank you for your interest in contributing to **Vulto OS**!

Vulto OS is an open-source, Arch Linux-based operating system focused on customization, usability, flexibility, and continuous improvement. Contributions of all kinds are welcome, including bug reports, documentation, testing, design, and code.

## Getting Started

Before contributing:

1. Read the project's `README.md`.
2. Check existing issues and pull requests to avoid duplicate work.
3. Make sure you understand the scope of your proposed change.
4. For significant changes, open an issue first to discuss the idea.

## Ways to Contribute

You can contribute by:

- Reporting bugs and installation problems.
- Testing ISO builds in virtual machines.
- Improving documentation and installation instructions.
- Fixing scripts, configuration files, and build issues.
- Improving the KDE Plasma live environment.
- Helping test Calamares and the installed system.
- Suggesting features, usability improvements, and design ideas.
- Improving accessibility, security, and reliability.

## Reporting Bugs

When opening a bug report, include as much relevant information as possible:

- A clear description of the problem.
- Steps to reproduce the issue.
- Expected behavior and actual behavior.
- The Vulto OS build or ISO version.
- Whether the issue occurred in a virtual machine or on physical hardware.
- Relevant error messages and logs.

**Please do not include passwords, private keys, access tokens, or other sensitive information in reports.**

## Submitting Changes

To contribute code or configuration changes:

1. Fork the repository.
2. Create a branch for your changes.
3. Make focused, clearly documented changes.
4. Test your changes before submitting them.
5. Commit your work with a descriptive commit message.
6. Open a pull request explaining what changed and why.

Keep pull requests focused on one problem or feature whenever possible. Smaller changes are easier to review and maintain.

## Development and Testing

Vulto OS is based on Arch Linux and uses Archiso to build its installation image.

During development:

- Test ISO builds in a virtual machine before using them on physical hardware.
- Verify that changes do not break the live session or installer.
- Avoid unnecessary changes to unrelated configuration files.
- Never run destructive installation or partitioning tests on a system containing important data.
- Do not commit generated ISO images, temporary build directories, package caches, or personal machine configuration unless explicitly required.

Build and testing instructions will be documented in the repository as the project evolves.

## Code and Configuration Guidelines

- Prefer clear, maintainable, and well-documented changes.
- Follow the conventions of the files and tools being modified.
- Explain non-obvious configuration decisions.
- Preserve compatibility with the project's Arch Linux base where practical.
- Consider security, accessibility, and the experience of new users.
- Do not introduce proprietary dependencies without discussing them first.

## Commit Messages

Use concise commit messages that describe the change.

Examples:

- `Fix live session startup`
- `Update Calamares configuration`
- `Improve installation documentation`
- `Add KDE Plasma packages`

## Pull Request Review

Pull requests may be reviewed for correctness, maintainability, security, documentation, and compatibility.

Additional changes or tests may be requested before a contribution is merged. Submitting a pull request does not guarantee acceptance.

## Licensing

By contributing, you agree that your contributions may be distributed under the project's **MIT License**, unless a different license is explicitly stated for the relevant files or components.

Please ensure that you have the right to submit any code, artwork, documentation, or other material you contribute.

Third-party components remain subject to their respective licenses.

## Community Standards

Be respectful, constructive, and welcoming.

- Critique ideas and code, not people.
- Be open to feedback and different approaches.
- Help keep discussions useful and inclusive.
- Do not submit malicious code or intentionally compromise system security.

## Project Status

Vulto OS is under active development. Features, architecture, and development practices may evolve as the project grows.

Thank you for helping make Vulto OS better!

**Vulto OS — Built on Arch Linux. Designed for freedom. Made to evolve.**
