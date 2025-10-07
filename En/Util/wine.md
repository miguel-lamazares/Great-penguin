# Windox 🍷

## Bottles 🍾
Wine environment manager to install and run Windows applications on Linux.

### Install FLATPAK
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
### Add the Flathub repository
```bash
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```
### Install Bottles
```bash
flatpak install flathub com.usebottles.bottles
```

### Run and configure Bottles
```bash
flatpak run com.usebottles.bottles
```

## Lutris 🦦
Platform to manage and install Windows games and applications using Wine.

## How to Install 🛠
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
Full virtualization of operating systems, including Windows, for running native applications.

## How to Install 🛠
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

## Resources
- [Official Wine documentation](https://wiki.winehq.org/)
- [Bottles](https://usebottles.com/)
- [Lutris](https://lutris.net/)
- [VirtualBox](https://www.virtualbox.org/)

## Notes
- It is recommended to always use updated versions of the software.
- Check each tool's documentation for advanced configurations.
- Performance may vary depending on hardware and the application used.
