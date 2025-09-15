# FastFetch 📊

O ```FastFetch``` é um programa de terminal que exibe informações do sistema de forma rápida e personalizável. Funciona como uma alternativa mais veloz ao Neofetch, mostrando detalhes de hardware, software e configurações. Sua principal vantagem é a alta customização via arquivos JSON, permitindo ajustar módulos, cores e layouts. Ideal para quem quer criar dashboards informativos com identidade visual única no terminal.

## Como Instalar 🛠
### Linux 🐧 
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

## Como usar 🔍

Para utilizar o ```FastFetch```, basta execultar o seguinte comando ```fastfatch```, consultar outros comandos, utilize ```fastfetch --help```.

### Customização 🚀

Use ```fastfetch --gen-config``` para gerar um arquivo de configuração padrão.

## Comunidade e Suporte 🌐 

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

4. Configure inicialização automática:

Abra o arquivo ```~/.zshrc``` com o editor nano:

```nano ~/.zshrc```

5. Adicione a seguinte linha no final do arquivo:
bash

```fastfetch -c ~/.config/fastfetch/pretty.jsonc```

6. Salve e recarregue:

Salve o arquivo com Ctrl + X, depois Y e Enter

7. Recarregue o terminal com:

```source ~/.zshrc```

### 🎩✨ A Mágica Está Pronta! Basta abrir novamente o terminal.