Install neovim and set up dotfiles symlinks on this machine.

Steps:
1. Install neovim via the system package manager (apt for Ubuntu/Debian, brew for macOS)
2. Clone https://github.com/T-Zoomer/dotfiles.git to ~/dotfiles if it doesn't already exist
3. Create ~/.config directory if it doesn't exist
4. Symlink ~/dotfiles/.config/nvim to ~/.config/nvim
5. Symlink ~/dotfiles/.ssh/config to ~/.ssh/config (create ~/.ssh if needed, chmod 700)

Run each step with appropriate sudo if needed. Report what was done.
