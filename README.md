# git-dotfiles

## Added commands

| Command             | Alias | Description                                         |
|---------------------|-------|-----------------------------------------------------|
| `git fixup`         | `gfu` | Adds current staged changes to the specified commit |
| `git branch-merged` | `gbm` | A command to run on a PR (GitHub Pull Request) branch that has just been merged into master and deleted and can also be deleted locally. It also rebases the master branch onto origin/master and checks it out. |

## Dependencies
I'm using [RichiH/vcsh](https://github.com/RichiH/vcsh) for dotfile management.

Currently the following arch packages are used:
- [lolcommits](https://aur.archlinux.org/packages/lolcommits/) to take a picture every time I commit

## How to use
```
# Install dependencies
yaourt -S lolcommits

# Clone
vcsh clone git@github.com:deiwin/git-dotfiles.git git

# Source the aliases (done automatically by my zsh conf)
source ~/.config/zshrc.d/git-aliases
```
