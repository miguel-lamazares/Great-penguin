# FastFetch 📊

```FastFetch``` es un programa de terminal que muestra información del sistema de forma rápida y personalizable. Funciona como una alternativa más rápida a Neofetch, mostrando detalles de hardware, software y configuraciones. Su principal ventaja es la alta personalización mediante archivos JSON, permitiendo ajustar módulos, colores y diseños. Ideal para quienes desean crear dashboards informativos con identidad visual única en el terminal.  

## Comó Instalar 🛠

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

## Comó usar 🔍

Para utilizar ```FastFetch```, simplemente ejecute el siguiente comando ```fastfatch```, Para consultar otros comandos, utilice ```fastfetch --help```.

### Personalización 🚀

Utilize ```fastfetch --gen-config``` Para generar un archivo de configuración predeterminado.

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

4. Configure el inicio automático:

Abra el archivo ```~/.zshrc``` con el editor nano:

```nano ~/.zshrc```

5. Agregue la siguiente línea al final del archivo :


```fastfetch -c ~/.config/fastfetch/pretty.jsonc```

6. Guardar y recaregue:

Guarde el archivo con Ctrl + X, luego Y y Enter

7. Recaregue el terminal con:

```source ~/.zshrc```

### 🎩✨ ¡La magia está lista! Simplemente vuelva a abrir el terminal. 