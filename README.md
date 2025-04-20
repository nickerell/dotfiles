# dotfiles

## Arch Process

### Git SSH and Stow
1. `yay -Syy git stow`
1. `ssh-keygen -C "nic-github"`
1. `cat ~/.ssh/id_e*.pub` generated file to place content in GitHub as SSH Key.
1. `git clone git@github.com:archlord333/dotfiles.git`
1. `cd dotfiles`
1. `stow .` 

### Terminal
1. `yay -Syy ttf-firacode-nerd nushell starship ghostty`
1. chsh -s /bin/nu

### Neovim (Would be nice to script with something like Ansible?)
1. `yay -Syy gopls lua-language-server pyright fd ripgrep wl-clipboard` (verify by typing lua-language-server to make sure it's on OS PATH) (verify NVIM understands with CMD "echo executable('lua-language-server')" results in 1 echoed)

## MacOS Process (Would be nice to script with something like Ansible?)

### Git SSH and Stow
1. `brew install git stow`
1. `ssh-keygen -C "nic-github"`
1. `cat ~/.ssh/id_e*.pub` generated file to place content in GitHub as SSH Key.
1. `git clone git@github.com:archlord333/dotfiles.git`
1. `cd dotfiles`
1. `stow .` 

### SKHD
1. Install from Approved Open Source Repo.
1. Copy skhd/skhdrc in this repo to ~/.config/skhd/skhdrc.

### Terminal
1. `brew install nushell` (MIT License, might also need openssl and cmake as dependencies)
1. Step here to change default shell on Mac to Nu.
1. Install FiraCode Nerd Font Mono from Approved OS Repo.
1. `brew install starship` (ISC License)
1. Install Ghostty from Approved OS Repo.

### Neovim
1. `brew install gopls lua-language-server pyright fd ripgrep` (all good MIT License or Apache 2 or BSD-3 (gopls))

### Notes
- fd and ripgrep are for Nvim Telescope and are just faster Rust-written utilities.
- 
