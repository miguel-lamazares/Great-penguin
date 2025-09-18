# ZSH 🐚

O ZSH (Z Shell) é um shell de linha de comando extremamente poderoso e altamente customizável para sistemas Unix-like (Linux, macOS). Ele é conhecido por seus recursos avançados de autocompletar, suporte a temas e plugins, e por ser altamente extensível. Tornou-se famoso graças ao framework Oh My Zsh, que simplifica sua configuração e management.

## Como Instalar 🛠️

### Linux 🐧

# Debian/Ubuntu
sudo apt install zsh

# Fedora
sudo dnf install zsh

# Arch Linux
sudo pacman -S zsh

### macOS 🍎

brew install zsh

#### Tornar o ZSH seu shell padrão

chsh -s $(which zsh)

## Como Usar 🔍

Após a instalação, reinicie o terminal ou execute:

zsh

#### Na primeira execução, o ZSH guiará você por uma configuração inicial básica.
##### Configuração Avançada com Oh My Zsh

Oh My Zsh é um framework de código aberto para gerenciar configurações do ZSH.

Instalação:

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

### Comandos úteis:


### Atualizar Oh My Zsh
omz update

### Desativar (temporariamente)
unset _ZOOM

### Reativar
source ~/.zshrc

## Customização 🎨
Estrutura de Diretórios


~/.zshrc              # Arquivo de configuração principal
~/.oh-my-zsh/         # Diretório do framework
~/.oh-my-zsh/themes/  # Temas instalados
~/.oh-my-zsh/plugins/ # Plugins instalados


### Plugins Úteis


plugins=(
  git
  docker
  kubectl
  zsh-autosuggestions
  zsh-syntax-highlighting
  git clone --depth 1 -- https://github.com/marlonrichert/zsh-autocomplete.git
)



Comunidade e Suporte 🌐

Consulte:

<a href="https://www.zsh.org/">Repositório oficial do ZSH</a>

<a href="https://github.com/ohmyzsh/ohmyzsh">Oh My Zsh no GitHub</a>

<a href="https://www.zsh.org/mla">Fórum da comunidade</a>
