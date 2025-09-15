# Spicetify 🎵

O ```Spicetify``` é uma ferramenta de linha de comando que permite personalizar completamente o cliente do Spotify, adicionando temas, extensões e modificações.

Existem rumores que as vezes ocorre um erro e os anuncios param de aparecer. 

## Como Instalar 🛠

### Linux 🐧 

```# curl -fsSL https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.sh | sh```

Para adicionar o marketplace
```curl -fsSL https://raw.githubusercontent.com/spicetify/marketplace/main/resources/install.sh | sh```

```spicetify backup apply```

### Windows 🪟

```iwr -useb https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.ps1 | iex ```

Para adicionar o marketplace
```iwr -useb https://raw.githubusercontent.com/spicetify/marketplace/main/resources/install.ps1 | iex```

```spicetify backup apply```

### MacOS 🍎

```brew install spicetify-cli```

Para adicionar o marketplace
```iwr -useb https://raw.githubusercontent.com/spicetify/marketplace/main/resources/install.ps1 | iex```

```spicetify backup apply```

## Comandos 🔧 

#### Gerenciamento Básico 📋

Aplicar configurações
```spicetify apply```

Restaurar backup
```spicetify restore```

Atualizar Spicetify
```spicetify upgrade```

#### Resetar Configurações 🔄

Restaurar original
```spicetify restore```

Reaplicar
```spicetify backup apply```

#### Problemas Comuns 🐛

Spotify atualizou?
```spicetify upgrade && spicetify apply```

Temas não funcionando?
```spicetify config current_theme Default && spicetify apply```

## Comunidade e Suporte 🌐 

<a href="https://spicetify.app/">Site oficial</a>
<a href="https://github.com/spicetify">repositório oficial</a>