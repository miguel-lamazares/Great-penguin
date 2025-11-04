# Atuin 🐢

```Atuin``` is a revolutionary tool that replaces your shell’s default history, using a SQLite database to store and synchronize your commands across devices.

## How to install 🛠

```curl --proto '=https' --tlsv1.2 -LsSf https://setup.atuin.sh | sh```

## How to use 🔍

Usage is very simple yet extremely useful: just press the up arrow key (↑) to navigate through your command history.  

With the help of nano:  

|Shell's | Path                    | Command                   |
|:-------|:---------------------------|:--------------------------|  
|Bash    | ~/.bashrc : eval           | eval "$(atuin init bash)" |
|Fish    | ~/.config/fish/config.fish | atuin init fish | source  |
|Zsh     | ~/.zshrc                   | eval "$(atuin init zsh)"  |

For more information, full documentation, reporting issues, or contributing, visit the project’s <a href="https://github.com/atuinsh/atuin">repository</a> and <a href="https://atuin.sh/">official website</a>.

