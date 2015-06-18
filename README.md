# git-dotfiles

## Added commands

| Command     | Alias | Description                                         |
|-------------|-------|-----------------------------------------------------|
| `git fixup` | `gfu` | Adds current staged changes to the specified commit |

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
