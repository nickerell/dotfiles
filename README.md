# dotfiles

## Arch Process

### Terminal
1. `yay -Syy nushell`
1. Copy nushell/ in this repo to ~/.config/nushell.
1. `yay -Syy ttf-firacode-nerd`
1. `yay -Syy starship`
1. Copy starship.toml to ~/.config/.
1. `yay -Syy ghostty`
1. Copy ghostty/config in this repo to ~/.config/ghostty/config.

### Neovim (Would be nice to script with something like Ansible?)
1. `yay -Syy gopls lua-language-server pyright fd ripgrep wl-clipboard` (verify by typing lua-language-server to make sure it's on OS PATH) (verify NVIM understands with CMD "echo executable('lua-language-server')" results in 1 echoed)
1. Copy neovim/ in this repo to ~/.config/neovim.

## MacOS Process (Would be nice to script with something like Ansible?)

### SKHD
1. Install from Approved Open Source Repo.
1. Copy skhd/skhdrc in this repo to ~/.config/skhd/skhdrc.

### Terminal
1. `brew install nushell` (MIT License)
1. Copy nushell/ in this repo to ~/.config/nushell.
1. Install Nerd Font from Approved OS Repo.
1. `brew install starship` (ISC License)
2. Copy starship.toml to ~/.config/.
1. Install Ghostty from Approved OS Repo.
1. Copy ghostty/config in this repo to ~/.config/ghostty/config.

### Neovim
1. `brew install gopls lua-language-server pyright fd ripgrep` (all good MIT License or Apache 2 or BSD-3 (gopls))
1. Copy neovim/ in this repo to ~/.config/neovim.

### Notes
- fd and ripgrep are for Nvim Telescope and are just faster Rust-written utilities.
- 
