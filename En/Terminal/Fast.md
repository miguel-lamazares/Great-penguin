# FastFetch 📊

```FastFetch``` is a terminal program that displays system information quickly and in a customizable way. It serves as a faster alternative to Neofetch, showing details about hardware, software, and configurations. Its main advantage is high customization via JSON files, allowing adjustment of modules, colors, and layouts. Ideal for those who want to create informative dashboards with a unique visual identity in the terminal.  


## How to install 🛠

### Linux 

```bash
Debian
sudo apt install fastfetch
```
```bash
Fedora
sudo dnf install fastfetch
```
```bash
Arch
sudo pacman -S fastfetch
```

## How to use 🔍

To use ```FastFetch```, simply run the following command ```fastfatch```,To see other commands, use ```fastfetch --help```.

### Customization 🚀

Use ```fastfetch --gen-config``` To generate a default configuration file.

Consulte em seu terminal com o comando ``` jp2a --help ``` ou no <a href="https://github.com/cslarsen/jp2a">repositório oficial no GitHub</a> para documentação completa.

# Customizações Previamente Configuradas 👺

<div align= "center"><img width="680" src="/imgs/Fast2.png"></div>

Uma das melhores características do FastFetch é sua alta customização e a facilidade para personalizá-lo.

Vou compartilhar meu tema atual e o passo a passo para configurar o seu:

#### 📂 Passo a Passo:


1. Acesse pastas ocultas:
Na pasta home do Linux, pressione simultaneamente ```Ctrl + H``` para visualizar pastas ocultas.

2. Navegue até a pasta do FastFetch:

Abra o diretório: ```/home/seu_usuario/.config/fastfetch/```

3. Adicione seus assets:

Crie uma pasta chamada ```assets```

Adicione uma imagem de sua preferência com o nome ```img.png```

Cole o arquivo de configuração disponível para download com o nome ```pretty.jsonc```

4. Configure automatic startup:

open the ```~/.zshrc```file with nano editor:

```nano ~/.zshrc```

5. Add the following line at the end of the file


```fastfetch -c ~/.config/fastfetch/pretty.jsonc```

6. Save and reload:

Save the file with Ctrl + X, then Y and Enter

7. Reload the terminal with:

```source ~/.zshrc```

### 🎩✨ The magic is ready! Just reopen the terminal.  