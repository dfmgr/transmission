## transmission  
  
Transmission is a cross-platform BitTorrent client  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/transmission/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install transmission transmission-gtk transmission-cli
```  

Fedora Based:

```shell
yum install transmission transmission-gtk transmission-cli
```  

Arch Based:

```shell
pacman -S transmission transmission-gtk transmission-cli
```  

MacOS:  

```shell
brew install transmission transmission-gtk transmission-cli
```
  
```shell
devnull kill -9 "$(pidof transmission-gt)"
devnull kill -9 "$(pidof transmission-daemon)"
devnull kill -9 "$(pidof transmission-remote-gtk)"
mv -fv "$HOME/.config/transmission" "$HOME/.config/transmission.bak"
git clone https://github.com/dfmgr/transmission "$HOME/.config/transmission"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/transmission" target="_blank" rel="noopener noreferrer">transmission wiki</a>  |  
  <a href="https://transmissionbt.com" target="_blank" rel="noopener noreferrer">transmission site</a>
</p>  
