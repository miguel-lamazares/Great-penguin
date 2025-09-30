# Spicetify 🎵

```Spicetify``` is a command-line tool that allows you to fully customize the Spotify client by adding themes, extensions, and modifications.

There are rumors that sometimes an error occurs and ads stop appearing.

## How to Install 🛠

### Linux 🐧 

```bash
curl -fsSL https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.sh | sh
```

To add the marketplace:
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

To add the marketplace:
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

To add the marketplace:
```powershell
iwr -useb https://raw.githubusercontent.com/spicetify/marketplace/main/resources/install.ps1 | iex
```

```bash
spicetify backup apply
```

## Commands 🔧 

#### Basic Management 📋

Apply configurations:
```bash
spicetify apply
```

Restore backup:
```bash
spicetify restore
```

Update Spicetify:
```bash
spicetify upgrade
```

#### Reset Configurations 🔄

Restore original:
```bash
spicetify restore
```

Reapply:
```bash
spicetify backup apply
```

#### Common Issues 🐛

Spotify updated?
```bash
spicetify upgrade && spicetify apply
```

Themes not working?
```bash
spicetify config current_theme Default && spicetify apply
```

## Community and Support 🌐 
For more information, full documentation, reporting issues, or contributing, visit the project's <a href="https://github.com/spicetify">repository</a> and <a href="https://spicetify.app/">official website</a>.
