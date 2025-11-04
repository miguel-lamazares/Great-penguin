# Atuin 🐢

O ```Atuin``` é uma ferramenta revolucionária que substitui o histórico padrão do seu shell, usando um banco de dados SQLite para armazenar e sincronizar seus comandos através de dispositivos.

## Como Instalar 🛠

```curl --proto '=https' --tlsv1.2 -LsSf https://setup.atuin.sh | sh```

## Como usar 🔍

eu uso é muito simples, porém extremamente útil: apenas pressione a tecla seta para cima (↑) para navegar pelo seu histórico de comandos.

com ajuda do nano:

|Shell's | Caminho                    | Comando                   |
|:-------|:---------------------------|:--------------------------|  
|Bash    | ~/.bashrc : eval           | eval "$(atuin init bash)" |
|Fish    | ~/.config/fish/config.fish | atuin init fish | source  |
|Zsh     | ~/.zshrc                   | eval "$(atuin init zsh)"  |

## Comunidade e Suporte 🌐 

Para mais informações, documentação completa, reportar issues ou contribuir, acesse o <a href="https://github.com/atuinsh/atuin">repositório</a> e <a href="https://atuin.sh/">site oficial</a> do projeto.

