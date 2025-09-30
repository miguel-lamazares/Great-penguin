# Jp2a 🎨

`jp2a` is a command-line (CLI) software designed to convert digital images in common formats (such as JPEG, PNG, GIF, among others) into ASCII art representations directly in the terminal or in text files. Its core functionality consists of analyzing the pixels of an image, mapping their brightness and color values to a set of text characters, and optionally using ANSI escape codes to incorporate colors, resulting in an approximate version of the original image composed entirely of characters.

## How to Install 🛠

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
## How to Use 🔍

To use `jp2a`, run the command followed by the path to the image file or a link to the desired image. If you want to customize the conversion, add optional parameters such as width, height, colors, or other adjustments. For example:

```bash
jp2a --width=50 --colors /path/Spain.png
```

You can combine multiple parameters as needed. To see all available parameters, use the command `jp2a --help` in the terminal.

### Basic Commands 🧰
```c
jp2a image.jpg                     # Basic conversion
jp2a --width=80 image.jpg          # Custom width
jp2a --height=25 image.jpg         # Custom height
jp2a --size=full image.jpg         # Use full terminal width
jp2a --size=half image.jpg         # Use half terminal width
```
### Color Commands 🖌️
```c
jp2a --colors image.jpg            # Colored output
jp2a --bg=dark image.jpg           # Dark background (optimization)
jp2a --bg=light image.jpg          # Light background (optimization)
jp2a --invert image.jpg            # Invert colors
```
### Output Commands 🖨️
```c
jp2a --output=art.txt image.jpg    # Save to file
jp2a --html image.jpg > page.html  # Output in HTML format
jp2a --ansi image.jpg              # Output with ANSI codes
```
### Customization Commands 🧩
```c
jp2a --chars="@#%&*+=-:. " image.jpg  # Custom characters
jp2a --fill=SIDE image.jpg            # Side fill
jp2a --border image.jpg               # Add border
jp2a --flipx image.jpg                # Flip horizontally
jp2a --flipy image.jpg                # Flip vertically
```
### Help Commands ❓
```c
jp2a --help                         # Show full help
jp2a --version                      # Show program version
```

Check your terminal with the command `jp2a --help` or visit the <a href="https://github.com/cslarsen/jp2a">official GitHub repository</a> for complete documentation.


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