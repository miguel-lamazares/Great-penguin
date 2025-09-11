# Jp2a 🎨

O ``` jp2a ``` é um software de linha de comando (CLI) projetado para converter imagens digitais, nos formatos mais comuns (tais como JPEG, PNG, GIF, entre outros), em representações de arte ASCII diretamente no terminal ou em arquivos de texto. Sua funcionalidade central consiste em analisar os pixels de uma imagem, mapear seus valores de brilho e cor para um conjunto de caracteres de texto e, opcionalmente, utilizar códigos de escape ANSI para incorporar cores, resultando em uma versão aproximada da imagem original composta inteiramente por caracteres.

## Como instalar 🛠

```bash
Debian
sudo apt install jp2a
```
```bash
Fedora
sudo dnf install jp2a
```
```bash
Arch
sudo pacman -S jp2a
```
## Como usar 🔍

Para utilizar o ```jp2a```, execute o comando seguido do caminho do arquivo de imagem ou de um link para a imagem desejada. Caso queira personalizar a conversão, adicione parâmetros opcionais, como largura, altura, cores ou outros ajustes. Por exemplo:

```bash
jp2a --width=50 --colors /caminho/Spain.png
```

Você pode combinar múltiplos parâmetros conforme necessário. Para consultar todos os parâmetros disponíveis, utilize o comando ```jp2a --help``` no terminal.

### Comando Básicos 🧰
```c
jp2a imagem.jpg                     # Conversão básica
jp2a --width=80 imagem.jpg          # Largura personalizada
jp2a --height=25 imagem.jpg         # Altura personalizada
jp2a --size=full imagem.jpg         # Usa largura total do terminal
jp2a --size=half imagem.jpg         # Usa metade da largura do terminal
```
### Comandos de Cores 🖌️
```c
jp2a --colors imagem.jpg            # Saída colorida
jp2a --bg=dark imagem.jpg           # Fundo escuro (otimização)
jp2a --bg=light imagem.jpg          # Fundo claro (otimização)
jp2a --invert imagem.jpg            # Inverte cores
```
### Comandos de Saída 🖨️
```c
jp2a --output=arte.txt imagem.jpg   # Salva em arquivo
jp2a --html imagem.jpg > page.html  # Saída em formato HTML
jp2a --ansi imagem.jpg              # Saída com códigos ANSI
```
### Comandos de Personalização 🧩
```c
jp2a --chars="@#%&*+=-:. " imagem.jpg  # Caracteres personalizados
jp2a --fill=LADO imagem.jpg          # Preenchimento lateral
jp2a --border imagem.jpg            # Adiciona borda
jp2a --flipx imagem.jpg             # Espelha horizontalmente
jp2a --flipy imagem.jpg             # Espelha verticalmente
```
### Comandos de Ajuda ❓
```c
jp2a --help                         # Mostra ajuda completa
jp2a --version                      # Mostra versão do programa
```


Consulte em seu terminal com o comando ``` jp2a --help ``` ou no <a href="https://github.com/cslarsen/jp2a">repositório oficial no GitHub</a> para documentação completa.


```c
,,,,'...   .oddd:..oXXXXk''''.'kXXX'.....kX0KXXkodNWN0,..';XNkcXN0....:;dXXO;     
c:;::::::;.;dddd,.'OXXXK,......'0NX'....;0XXOl,...,ONO'....OX;.lNN;...;,o0NX;     
;:::::::::,c:;;lolxXXXXx........OXXo;,;oKXXX;.......xN0oloONXx:xk:;...':dONN,  ...
',;;;:::c:'    .ooc:xXNX,......d00O0000K0000x.......oNNOo:;;oXNO...';;',cxko......
..';;:::::'    'l.   c0XKl;,,:k0KKKKKKKKKKKXXKxo:cxKNXc......kNK:;x,;;,..lx,....''
.,,;;:::::'   'o,    ;odddk00XXXKKKKKKKKKKKKKKXXXX0O00:.....dXNk;cx,',,..;;....'',
;::c:::::;' .'od,   .lolx0XKKKKKKKKKKKKKKKKKKKKKKKKKXKOc...'l0:...:,;;;;..........
;:ONd::;;;,''.,oo;''cxOXXKKKKKKKKKKKKKKKKKKKKKKKKKKKKKXX0kOXNl....,,;;::'.........
;;:l:;;;,,,'   .old0XXXKKKKKKKKKXXO0kOkOOOKXXXXXXKKKKKK0KXKOXx,'...,,;;;,.........
;;;;,,,,,,,''. .ldXXXKKKKKKKXXXKOoc;;;;,.,;::cok0KKkk0OOkXdlood;...,,;;;;......l0'
;,,'''.'''''...'ccx0OKO00XX0kdc;;;;;,;;;,;:::;;,,:OOkkkk0xccl,..''..;:;;;,......'.
,'.............;xc:lkxkdxKx:'.',,,,,',:;,',,,;,..,ol;;::;.:dk'......;;::::'.......
..........;'...::ok;.':;,;x0OoxKOc,,',;,''',:x00k00d;,;. ,l,l'......;,...;........
..........cc,...;';d. ,;,',;;;;,',;;;;ookxdc,,;;,,,;:lc. ;,:d..,c. ......;........
....:ccc:,,:c:;,:c',l cxxollccloxkc::,kdOOOOkxdoooxk00o ,',xcccc;...::...',.......
,.. .:ccccc;:ccc:cc;d'.kOOOOOOOOOOc;;'ooOOOOOOOOOOOO0O. c,dlccc:,;ccc:....:. .....
c:::;;ccccccccc;c:cxoo ;OOOOkOOkOOxc;,;xkOOkkkkkkOO00c ':xc:cc:;:cccc'. ..;'.cccc,
::::::::::cccc:.,::o;c; :OOOOOOkOOOkxloxkOOOOOkkkOOOo''d,:',,'.;cc::' . ..';.:c;..
:::;;::;,'.',;:'...  ;' .:kOOkkOOOOxxxkkkkxxkOOOOO0o .,c.   ..,;,,::;.dl...:.,:,:c
:::''::cc:;....'..... ..,,lkOOOkkc;:llollll;;dO0KK0:.;    ......';;,,.:o...;,.cccc
:::'..'''',,.......'.;,.,:,:kOOOOkxxddoooodxkOO0XNKxd:  .';,..........;x....:.:ccc
::::'...........,lolll::,cc;;lkOOOOOoc.;:okOOOOOxxOkd;..,cdkkc'.....,, .. ..:.'ccc
',,,,........;lkkoccclll,:::;;;cxx,;.; ..;:cOkc;codoc;;cccclxOOo,.....  . ..,,.ccc
.........':okkkkd::ccooc,:::;;;;,...... ....';;:;lll:;;cccccokOOOo,.... ck'..:.;cc
.........xxdxxxxl::ccll,::;;;;;:::;,',;::::::::;'okk:;,c:ccclkkOOkkl'.. ;K...:...'
.........o:;;lxkl::cc;,;;;;;;;;;;;;;;,,;::::::;;dOOOo;,;;ccclkkkd;:xl....k...,;..,
.........c:::;xxo::::',;;;;;:dd:;;;;;;;;:;:::ccxkkkkkc;',clxdkkk::cdl....x. ..:...
.........::::,lxx::::,;;;;:o:xdc:;;;;;;;;;:lxdokkkkkkkc,.clOkkkd;ccol... ';...;'.:
.........;:::::xxo:::';;;;oxd:,'ddl:;;;;:lxkxckkkkkkkkkc,::cxkkc:cclc.... ....';.;
.........,::::,dxxl::.,,;lxxxxc''okkdddxkkkxcxxxxxxxxkkkl;:okko::cclc....  ....c..
.........;::::;;xxxc;,c:coooodxd:'lxxxxxxxxcdxxxdoooodddd;lxkx;::cccc..... . ..;,.
.........::::;'.lxxdl:xxxxxxxdoool:loxxxxdlooooddxxxxxxxd:xxxc';:cccl..... d:...:.
.........lcc:'.',dxxdcdxxxxxxxxxxxdol:oxl:odxxxxxxxxxxxxdlxxd;,.':ccl..... :c ..:.
........,oool;:,';dxdcddddddddddxdxxxdxxodxxxxxxxxxxxxxxolxx,:,,',,:c......:d.,l;'
........:ccolcc',.lxd;;dxxxddoddddddxxxl:ldxxxxxodxxxxxd;ox:;:':'o:.'...... '.':.;
..........','::';.'od:..,oxxd'cddddddddolodxxxx:'xxxxd,  ol:l;;c,xx........  . ..;
.............:c,;';,dc'  .cod'.dxddddddldddddxo ;l:,'.  'l;dl'ol,xx......... '. .'
.............;c,;:,;:l',,,...  ,oddddddcddddxx:  .,:cc:,.;dx:;do;xc......... :c ..
...........;,:l':o,c;ccxkddddl;. 'oddddcdddxd' 'oxxxxxxd,odd,odo::',,,...... .c ..
...........;;lo,:o:cl,,dkdo::cdd' .do:,.,:od, :dxdlcoddd;ddccddolod::;.....,..c  .
..........,colo;;oocoo.ldo. . :dc  '..... .l..ddd;...ddo;ddcddddddc;:l....::, ;. .
```