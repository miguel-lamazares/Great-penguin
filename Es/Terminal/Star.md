curl -sS https://starship.rs/install.sh | sh

bash : ~/.bashrc : eval "$(starship init bash)"
fish : ~/.config/fish/config.fish : starship init fish | source
Zsh  : ~/.zshrc: eval "$(starship init zsh)"

entre no site para escolher um tema basta copia-lo e cola-lo no terminal 