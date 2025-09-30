# FastFetch 📊

`FastFetch` is a terminal program that displays system information quickly and in a customizable way. It serves as a faster alternative to Neofetch, showing details about hardware, software, and configurations. Its main advantage is high customization via JSON files, allowing adjustment of modules, colors, and layouts. Ideal for those who want to create informative dashboards with a unique visual identity in the terminal.

## How to install 🛠

### Linux

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

## How to use 🔍

To use `FastFetch`, simply run the following command: `fastfetch`.  
To see other commands, use `fastfetch --help`.

### Customization 🚀

Use `fastfetch --gen-config` to generate a default configuration file.

Check your terminal with the command `jp2a --help` or visit the <a href="https://github.com/cslarsen/jp2a">official GitHub repository</a> for complete documentation.

# Preconfigured Customizations 👺

<div align="center"><img width="680" src="/imgs/Fast2.png"></div>

One of the best features of FastFetch is its high customizability and the ease of personalizing it.

I'll share my current theme and the step-by-step guide to configure yours:

<a href="/Config-fastfetch">Click here</a>

#### 📂 Step-by-step:

1. Access hidden folders:  
In your Linux home folder, press `Ctrl + H` simultaneously to view hidden folders.

2. Navigate to the FastFetch folder:  
Open the directory: `/home/your_user/.config/fastfetch/`

3. Add your assets:  
Create a folder named `assets`  
Add an image of your choice named `img.png`  
Paste the configuration file available for download and name it `pretty.jsonc`

4. Configure automatic startup:  
Open the `~/.zshrc` file with the nano editor:

```nano ~/.zshrc```

5. Add the following line at the end of the file:

```fastfetch -c ~/.config/fastfetch/pretty.jsonc```

6. Save and reload:  
Save the file with Ctrl + X, then Y and Enter

7. Reload the terminal with:

```source ~/.zshrc```

### 🎩✨ The magic is ready! Just reopen the terminal.
