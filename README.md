# Conventional Commits Emoji git hook

`commit-msg` git hook written in JS to append to commit message an emoji corresponding to the specified [conventional commit](https://www.conventionalcommits.org/en/v1.0.0/) type.

Requirement: [Node.js](https://nodejs.org/en/)

## Supported types and related Emojis

| Conventional Commit type | Related Emoji | Context |
| ------------------------ | ------------- | ------- |
| `feat`                   | ✨            | adds new functionality / improves something |
| `test`                   | 🧪            | adds or updates unit tests |
| `fix`                    | 🐛            | fixes a bug or issue |
| `docs`                   | 📚            | adds or improves documentation |
| `style`                  | 💎            | makes changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc) |
| `refactor`               | 🔨            | refactors existing code |
| `ci`                     | ⚙️            | changes CI/CD configuration files and scripts |
| `perf`                   | 🚀            | improves performance |
| `build`                  | 🛠            | makes changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm, etc) |
| `chore`                  | 🧹            | makes other chore changes that don't modify src or test files |
| `revert`                 | 🗑             | reverts some preceding code |
