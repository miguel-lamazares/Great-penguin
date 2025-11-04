# Atuin 🐢

```Atuin``` es una herramienta revolucionaria que reemplaza el historial predeterminado de su shell, utilizando una base de datos SQLite para almacenar y sincronizar sus comandos entre dispositivos.

## Cómo instalar 🛠

```curl --proto '=https' --tlsv1.2 -LsSf https://setup.atuin.sh | sh```

## Cómo usar 🔍

El uso es muy sencillo, pero extremadamente útil: simplemente presione la tecla de flecha hacia arriba (↑) para navegar por su historial de comandos.  

Con la ayuda de nano:  

|Shell's | Ruta                    | Comando                   |
|:-------|:---------------------------|:--------------------------|  
|Bash    | ~/.bashrc : eval           | eval "$(atuin init bash)" |
|Fish    | ~/.config/fish/config.fish | atuin init fish | source  |
|Zsh     | ~/.zshrc                   | eval "$(atuin init zsh)"  |

Para más información, documentación completa, reportar issues o contribuir, visite el<a href="https://github.com/atuinsh/atuin">repositorio</a> y <a href="https://atuin.sh/">sitio oficial</a> del proyecto.

