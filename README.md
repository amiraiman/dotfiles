# Dotfiles

Files & folders location in this repo are mapped to their actual location on a filesystem, except for: 
- `home/*` mapped to `$HOME/*`

## DE

### Gnome

@`/scripts/gnome.sh`
1. Set workspaces to 10 (fixed)
2. Change hotkey for switch-to-workspace to `mod+n` (0 -> 10)
3. Change hotkey for move-to-workspace to `mod+shift+n` (0 -> 10)

### Terminal

- wezterm [Install](https://wezterm.org/install/linux.html)
- zsh [Install](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH)
- omz [Install](https://github.com/ohmyzsh/ohmyzsh/wiki)
- zsh-autosuggestions [Install](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh)
- tmux [Build](https://github.com/tmux/tmux/wiki/Installing#from-source-tarball)
- httpie [Install](https://httpie.io/cli)
- fzf [Install](https://github.com/junegunn/fzf?tab=readme-ov-file#Installation)
- ripgrep [Install](https://github.com/BurntSushi/ripgrep?tab=readme-ov-file#installation)
- lsd [Install](https://github.com/lsd-rs/lsd?tab=readme-ov-file#Installation)

### Dev Env
- nvim [Install](https://github.com/neovim/neovim/releases)
- lazyvim [Install](https://www.lazyvim.org/installation)

## Config

### Keyd

@`/etc/keyd/default.conf`
Swap `capslock` with `esc`, and overload it with `ctrl` to become `ctrl` when held and `esc` when pressed.

### Zsh & OMZ

@`/home/.zshrc`
zsh & oh-my-zsh with some sane plugins enabled:
- git
- vi-mode
- zsh-autosuggestions

### Wezterm

@`/home/.wezterm.lua`
sane defaults (fonts, theme)
