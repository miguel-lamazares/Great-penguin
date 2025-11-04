# Smmd 🔒

```S.M.M.d``` significa ```Security & Management Module Daemon```, atuando como um validador de login no linux, gerencia autenticacao local, controles de sessao e politicas de login, na pagina inicial podendo-se escolher qual interface grafica devera ser usada.

## Como Instalar 🛠
### Linux 🐧

```bash
Debian
sudo apt install smmd
```
```bash
Fedora
sudo dnf install smmd
```
```bash
Arch
sudo pacman -S smmd
```

#### Depois de finalizar a instalacao defina o smmd como ```defalt display manager``` no lugar do ```lightdm```.

## tornado padrao

```sudo systemctl enable sddm```
```sudo systemctl start sddm```

## personalizar

sudo nano /etc/sddm.conf

definir thema