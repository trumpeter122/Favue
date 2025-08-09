# Development Guidelines

## Commit conventions




Based on my analysis of the repository, the **fastapi/full-stack-fastapi-template** uses an **emoji-based commit convention** similar to Gitmoji. Here are the key aspects of their commit convention:

## Commit Message Format

The repository uses emoji prefixes to categorize different types of changes:

* `🐛` for bug fixes
* `✨` for new features  
* `♻️` for refactors
* `📝` for documentation
* `⬆` for dependency upgrades
* `🔧` for configuration changes
* `👷` for CI/CD related changes
* `🎨` for UI/styling improvements
* `🔥` for removing code/files
* `✅` for adding/updating tests [1](#0-0) 

## Dependency Updates

For automated dependency updates via Dependabot, the repository specifically uses the `⬆` prefix: [2](#0-1) 

## Pull Request Labels

The repository enforces that PRs must have one of the following labels, which correspond to commit categories: [3](#0-2) 

## Release Notes Integration

The commit convention is integrated with their automated release notes system, where commits are categorized by type and automatically added to the release notes based on PR labels. [4](#0-3) 

## Notes

The repository doesn't appear to have a formal CONTRIBUTING.md file that explicitly documents these conventions, but the pattern is consistently followed throughout the project history and enforced through GitHub Actions workflows. The emoji-based approach makes it easy to visually scan commit history and automatically categorize changes for release notes.
