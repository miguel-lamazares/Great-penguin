# Spicetify 🎵

`Spicetify` es una herramienta de línea de comandos que permite personalizar completamente el cliente de Spotify, añadiendo temas, extensiones y modificaciones.

Se rumorea que a veces ocurre un error y los anuncios dejan de aparecer.

## Cómo instalar 🛠

### Linux 🐧

```bash
curl -fsSL https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.sh | sh
```

Para añadir el marketplace:
```bash
curl -fsSL https://raw.githubusercontent.com/spicetify/marketplace/main/resources/install.sh | sh
```

```bash
spicetify backup apply
```

### Windows 🪟

```powershell
iwr -useb https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.ps1 | iex
```

Para añadir el marketplace:
```powershell
iwr -useb https://raw.githubusercontent.com/spicetify/marketplace/main/resources/install.ps1 | iex
```

```powershell
spicetify backup apply
```

### MacOS 🍎

```bash
brew install spicetify-cli
```

Para añadir el marketplace:
```powershell
iwr -useb https://raw.githubusercontent.com/spicetify/marketplace/main/resources/install.ps1 | iex
```

```bash
spicetify backup apply
```

## Comandos 🔧

#### Gestión básica 📋

Aplicar configuraciones:
```bash
spicetify apply
```

Restaurar copia de seguridad:
```bash
spicetify restore
```

Actualizar Spicetify:
```bash
spicetify upgrade
```

#### Restablecer configuraciones 🔄

Restaurar original:
```bash
spicetify restore
```

Reaplicar:
```bash
spicetify backup apply
```

#### Problemas comunes 🐛

¿Spotify se actualizó?
```bash
spicetify upgrade && spicetify apply
```

¿Temas no funcionan?
```bash
spicetify config current_theme Default && spicetify apply
```

## Comunidad y soporte 🌐

Para más información, documentación completa, reportar problemas o contribuir, visita el <a href="https://github.com/spicetify">repositorio</a> y el <a href="https://spicetify.app/">sitio oficial</a> del proyecto.
