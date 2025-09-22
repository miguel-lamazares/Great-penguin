# Jp2a 🎨

O ``` jp2a ``` es un software de línea de comandos (CLI) diseñado para convertir imágenes digitales, en los formatos más comunes (como JPEG, PNG, GIF, entre otros), en representaciones de arte ASCII directamente en el terminal o en archivos de texto. Su funcionalidad principal consiste en analizar los píxeles de una imagen, mapear sus valores de brillo y color a un conjunto de caracteres de texto y, opcionalmente, utilizar códigos de escape ANSI para incorporar colores, resultando en una versión aproximada de la imagen original compuesta completamente por caracteres.

## Comó instalar 🛠

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
## Comó usar 🔍

Para utilizar o ```jp2a```, ejecuta el comando seguido de la ruta del archivo de imagen o de un enlace a la imagen deseada. Si deseas personalizar la conversión, agrega parámetros opcionales, como ancho, alto, colores u otros ajustes. Por ejemplo:

```bash
jp2a --width=50 --colors /caminho/Spain.png
```
Puedes combinar múltiples parámetros según sea necesario. Para consultar todos los parámetros disponibles, utiliza el comando ```jp2a --help``` no terminal.

### Comandos Básicos 🧰
```c
jp2a imagem.jpg                     # Conversión básica
jp2a --width=80 imagem.jpg          # Ancho personalizado
jp2a --height=25 imagem.jpg         # Alto personalizado
jp2a --size=full imagem.jpg         # Usar ancho total del terminal
jp2a --size=half imagem.jpg         # Usar la mitad del ancho del terminal
```
### Comandos de Colores 🖌️
```c
jp2a --colors imagem.jpg            # Salida en color
jp2a --bg=dark imagem.jpg           # Fondo oscuro (optimización)
jp2a --bg=light imagem.jpg          # Fondo claro (optimización)
jp2a --invert imagem.jpg            # Invertir colores
```
### Comandos de Salida 🖨️
```c
jp2a --output=arte.txt imagem.jpg   # Guardar en archivo
jp2a --html imagem.jpg > page.html  # Salida en formato HTML
jp2a --ansi imagem.jpg              # Salida con códigos ANSI
```
### Comandos de Personalización 🧩
```c
jp2a --chars="@#%&*+=-:. " imagem.jpg  # Caracteres personalizados
jp2a --fill=LADO imagem.jpg          # Relleno lateral
jp2a --border imagem.jpg            # Añadir borde
jp2a --flipx imagem.jpg             # Voltear horizontalmente
jp2a --flipy imagem.jpg             # Voltear verticalmente
```
### Comandos de Ayuda ❓
```c
jp2a --help                         # Mostrar ayuda completa
jp2a --version                      # Mostrar versión del programa
```


Consulta en tu terminal con el comando ``` jp2a --help ``` o en el <a href="https://github.com/cslarsen/jp2a">repositório oficial en GitHub</a> para la documentación completa.


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
