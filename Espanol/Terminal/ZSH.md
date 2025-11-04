# ZSH 🐚

ZSH (Z Shell) es un shell de línea de comandos extremadamente potente y altamente personalizable para sistemas Unix-like (Linux, macOS). Es conocido por sus funciones avanzadas de autocompletado, soporte para temas y plugins, y por ser muy extensible. Se hizo famoso gracias al framework Oh My Zsh, que simplifica su configuración y gestión.

## Cómo instalar 🛠️

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

#### Hacer de ZSH tu shell predeterminado

```chsh -s $(which zsh)```

## Cómo usar 🔍

Después de la instalación, reinicia la terminal o ejecuta:

```zsh```

#### En la primera ejecución, ZSH te guiará por una configuración inicial básica.
##### Configuración avanzada con Oh My Zsh

Oh My Zsh es un framework de código abierto para gestionar configuraciones de ZSH.

Instalación:

```sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```

### Comandos útiles:


### Actualizar Oh My Zsh
```omz update```

### Desactivar (temporalmente)
```unset _ZOOM```

### Reactivar
```source ~/.zshrc```

## Personalización 🎨
Estructura de directorios


1. ~/.zshrc              # Archivo principal de configuración
2. ~/.oh-my-zsh/         # Directorio del framework
3. ~/.oh-my-zsh/themes/  # Temas instalados
4. ~/.oh-my-zsh/plugins/ # Plugins instalados


### Plugins útiles


plugins={
```git```
```docker```
```kubectl```
```zsh-autosuggestions```
```zsh-syntax-highlighting```
```git clone --depth 1 -- https://github.com/marlonrichert/zsh-autocomplete.git```
}



## Comunidad y soporte 🌐

Consulta:

<a href="https://www.zsh.org/">Repositorio oficial de ZSH</a>

<a href="https://github.com/ohmyzsh/ohmyzsh">Oh My Zsh en GitHub</a>

<a href="https://www.zsh.org/mla">Foro de la comunidad</a>

