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

Consulta en tu terminal con el comando ``` jp2a --help ``` o en el <a href="https://github.com/cslarsen/jp2a">repositorio oficial en GitHub</a> para la documentación completa.

# Personalizaciones Previamente Configuradas 👺

<div align= "center"><img width="680" src="/imgs/Fast2.png"></div>

Una de las mejores características de FastFetch es su alta personalización y la facilidad para adaptarlo a tu gusto.

Voy a compartir mi tema actual y el paso a paso para que configures el tuyo:

<a href="/Config-fastfetch">Clique aqui</a>

#### Paso a Paso 📂:

1. Accede a las carpetas ocultas:
En la carpeta home de Linux, presiona simultáneamente ```Ctrl + H``` para visualizar las carpetas ocultas.

2. Navega hasta la carpeta de FastFetch:

Abre el directorio: ```/home/seu_usuario/.config/fastfetch/```

3. Añade tus assets:

Crea una carpeta llamada ```assets```

Añade una imagen de tu preferencia con el nombre ```img.png```

Pega el archivo de configuración disponible para descargar con el nombre ```pretty.jsonc```

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
