curl --proto '=https' --tlsv1.2 -LsSf https://setup.atuin.sh | sh

bash : ~/.bashrc : eval "$(atuin init bash)"
fish : ~/.config/fish/config.fish : atuin init fish | source
Zsh  : ~/.zshrc: eval "$(atuin init zsh)"