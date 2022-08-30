## 👋 Welcome to mate 🚀


  
  
### Requires scripts to be installed

```shell
sudo bash -c "$(curl -q -LSsf <https://github.com/desktopmgr/installer/raw/main/install.sh>)" && sudo desktopmgr install installer
```

OR

### Automatic install/update  

```shell
desktopmgr update mate
```

OR

```shell
bash -c "$(curl -q -LSsf https://github.com/desktopmgr/mate/raw/main/install.sh)"
```
  
requirements:
  
Debian based:

```shell
apt install mate
```  

Fedora Based:

```shell
yum install mate
```  

Arch Based:

```shell
pacman -S mate
```  

MacOS:  

```text
Only linux is supported
```
  
Manual install:  

  ```shell
APPDIR="$HOME/.local/share/CasjaysDev/desktopmgr/mate"
mv -fv "$HOME/.config/mate" "$HOME/.config/mate.bak"
git clone "https://github.com/desktopmgr/mate" "$APPDIR"
cp -Rfv "$APPDIR/etc/." "$HOME/.config/mate/"
[ -d "$APPDIR/bin" ] && cp -Rfv "$APPDIR/bin/." "$HOME/.local/bin/"
```

## Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
⛵ desktopmgr: [Github](https://github.com/desktopmgr) ⛵  
  
## Links

<p align=center>
  <a href="https://wiki.archlinux.org/index.php/mate" target="_blank" rel="noopener noreferrer">mate wiki</a>  |  
  <a href="mate" target="_blank" rel="noopener noreferrer">mate site</a>
</p>  
