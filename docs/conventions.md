# conventions

## Commit Style

Commit and PR titles should follow [The Conventional Commits][conventional-commits] specification.

[conventional-commits]: https://www.conventionalcommits.org/en/v1.0.0

Available types:

- **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
- **chore**: Other changes that don't modify src or test files
- **ci**: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
- **docs**: Documentation only changes
- **feat**: A new feature
- **fix**: A bug fix
- **perf**: A code change that improves performance
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- **test**: Adding missing tests or correcting existing tests

References:
- https://www.conventionalcommits.org/en/v1.0.0
- https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716
- https://karma-runner.github.io/1.0/dev/git-commit-msg.html
- https://sparkbox.com/foundry/semantic_commit_messages
- https://github.com/conventional-changelog/commitlint/tree/master/%40commitlint/config-conventional
