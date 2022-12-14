# Conventional Commits Emoji git hook

`commit-msg` git hook written in JS to append to commit message an emoji corresponding to the specified [conventional commit](https://www.conventionalcommits.org/en/v1.0.0/) type.

Requirement: [Node.js](https://nodejs.org/en/)

## Supported types and related Emojis

| Conventional Commit type | Related Emoji | Context |
| ------------------------ | ------------- | ------- |
| `feat`                   | โจ            | adds new functionality / improves something |
| `test`                   | ๐งช            | adds or updates unit tests |
| `fix`                    | ๐            | fixes a bug or issue |
| `docs`                   | ๐            | adds or improves documentation |
| `style`                  | ๐            | makes changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc) |
| `refactor`               | ๐จ            | refactors existing code |
| `ci`                     | โ๏ธ            | changes CI/CD configuration files and scripts |
| `perf`                   | ๐            | improves performance |
| `build`                  | ๐             | makes changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm, etc) |
| `chore`                  | ๐งน            | makes other chore changes that don't modify src or test files |
| `revert`                 | ๐             | reverts some preceding code |
