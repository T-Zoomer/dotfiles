# dotfiles

Personal dotfiles for jeeves and other machines.

## Contents

- `.config/nvim/` — Neovim config (kickstart-based)
- `.ssh/config` — SSH aliases (e.g. `ssh jeeves`)

## Setup

Run the Claude skill to automatically install neovim and symlink everything:

```
/setup
```

Or manually:

```bash
git clone https://github.com/T-Zoomer/dotfiles.git ~/dotfiles

# Neovim
sudo apt install neovim           # Ubuntu
# brew install neovim             # macOS

# Symlinks
mkdir -p ~/.config ~/.ssh
ln -sf ~/dotfiles/.config/nvim ~/.config/nvim
ln -sf ~/dotfiles/.ssh/config ~/.ssh/config
chmod 700 ~/.ssh
```
