# ZSH 🐚

ZSH (Z Shell) is an extremely powerful and highly customizable command-line shell for Unix-like systems (Linux, macOS). It is known for its advanced autocomplete features, support for themes and plugins, and high extensibility. ZSH became popular thanks to the Oh My Zsh framework, which simplifies its configuration and management.

## How to Install 🛠️

### Linux 🐧
```bash
Debian/Ubuntu
sudo apt install zsh

Fedora
sudo dnf install zsh

Arch Linux
sudo pacman -S zsh
```
### macOS 🍎

```brew install zsh```

#### Make ZSH your default shell

```chsh -s $(which zsh)```

## How to Use 🔍

After installation, restart your terminal or run:

```zsh```

#### On first run, ZSH will guide you through a basic initial setup.
##### Advanced Configuration with Oh My Zsh

Oh My Zsh is an open-source framework for managing ZSH configurations.

Installation:

```sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```

### Useful Commands:


### Update Oh My Zsh
```omz update```

### Temporarily Disable
```unset _ZOOM```

### Reactivate
```source ~/.zshrc```

## Customization 🎨
Directory Structure

1. ~/.zshrc              # Main configuration file
2. ~/.oh-my-zsh/         # Framework directory
3. ~/.oh-my-zsh/themes/  # Installed themes
4. ~/.oh-my-zsh/plugins/ # Installed plugins

### Useful Plugins

plugins={
```git```
```docker```
```kubectl```
```zsh-autosuggestions```
```zsh-syntax-highlighting```
```git clone --depth 1 -- https://github.com/marlonrichert/zsh-autocomplete.git```
}

## Community and Support 🌐

See:

<a href="https://www.zsh.org/">Official ZSH repository</a>

<a href="https://github.com/ohmyzsh/ohmyzsh">Oh My Zsh on GitHub</a>

<a href="https://www.zsh.org/mla">Community forum</a>
