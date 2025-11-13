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

## Torna-lo padrão do sistema 🏗️

```sudo systemctl enable sddm```
```sudo systemctl start sddm```

## Thema personalizado 🎨

1. Adicione o tema desejado em ```/usr/share/smmd/themes/```
2. apos o primeiro passo, apenas faca referencia ao tema em ``````sudo nano /etc/sddm.conf`````` 

## Compatibilidade 🏰

* GNOME

* KDE Plasma

* XFCE

* LXQt

* i3wm

* Outros ambientes X11 e Wayland

O SMMD oferece uma alternativa segura e customizável aos display managers tradicionais, com foco em segurança e controle granular sobre sessões de usuário.

## Comunidade e Suporte 🌐 

<a href="https://github.com/smmd-project/smmd">GitHub 🐙</a> 
<a href="https://smmd-project.org">Site Oficia 🌐l</a>
<a href"https://forum.smmd-project.org">Fórum Oficial 💬</a>
<a href="https://github.com/smmd-themes">SMMD Themes 🎨 </a>
<a href="https://forum.manjaro.org/c/display-managers">Linux Display Managers 🎨 </a>
