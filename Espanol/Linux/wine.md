# Windox 🍷

## Bottle 🍾
Administrador de entornos Wine para instalar y ejecutar aplicaciones de Windows en Linux.

### Instala FLATPAK
```bash
sudo apt install flatpak
```
```bash
Fedora
sudo dnf install flatpak
```
```bash
Arch
sudo pacman -S flatpak
```
### Agrega el repositorio Flathub
```bash
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```
### Instala Bottle
```bash
flatpak install flathub com.usebottles.bottles
```

### Ejecuta y configura Bottle
```bash
flatpak run com.usebottles.bottles
```

## Lutris 🦦
Plataforma para gestionar e instalar juegos y aplicaciones de Windows usando Wine.

## Cómo instalar 🛠
### Linux 🐧

```bash
Debian
sudo apt install lutris
```
```bash
Fedora
sudo dnf install lutris
```
```bash
Arch
sudo pacman -S lutris
```

## VirtualBox 📦
Virtualización completa de sistemas operativos, incluyendo Windows, para usar aplicaciones nativas.

## Cómo instalar 🛠
### Linux 🐧

```bash
Debian
sudo apt install virtualbox
```
```bash
Fedora
sudo dnf install virtualbox
```
```bash
Arch
sudo pacman -S virtualbox
```

## Recursos
- [Documentación oficial de Wine](https://wiki.winehq.org/)
- [Bottles](https://usebottles.com/)
- [Lutris](https://lutris.net/)
- [VirtualBox](https://www.virtualbox.org/)

## Notas
- Se recomienda utilizar siempre versiones actualizadas de los programas.
- Consulta la documentación de cada herramienta para configuraciones avanzadas.
- El rendimiento puede variar según el hardware y la aplicación utilizada.
