# dotfiles

### New Machine Set Up

## Arch Linux

1. `sudo pacman -Syy chezmoi`
1. `chezmoi init --ssh --apply nickerell`

## Mac

1. `xcode-select --install`
1. `sh -c "$(curl -fsLS https://get.chezmoi.io)" -- init --ssh --apply nickerell`
1. Might need to close current shell to get zsh path updates.
1. `pass-cli login`
1. `chezmoi apply`
