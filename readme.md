# `gh branch` GitHub CLI extension

[GitHub CLI](https://github.com/cli/cli) extension for fuzzy finding, quickly switching between, and deleting branches. 

## Installation
```
gh extension install mislav/gh-branch
```

This extension depends on [fzf](https://github.com/junegunn/fzf#readme) as a fuzzy finder. To install using Homebrew:
```
brew install fzf
```

See the fzf documentation for details on installing on [Windows](https://github.com/junegunn/fzf#windows) and [Linux](https://github.com/junegunn/fzf#using-linux-package-managers)

## Usage
```
gh branch
```

Displays an interactive branch switcher that lists local branches in relation
to the pull requests in the repository. The selected branch is checked out.

<!-- You can also select multiple branches with Tab and press Ctrl-D to delete them. -->
