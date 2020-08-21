## transmission  
  
Transmission is a cross-platform BitTorrent client  
  
requires:    
apt: ```apt install transmission-gtk transmission-cli```  
yum: ```yum install transmission-gtk transmission-cli```  
pacman: ```pacman -S transmission-gtk transmission-cli```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/transmission/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/transmission" "$HOME/.config/transmission.bak"
git clone https://github.com/dfmgr/transmission "$HOME/.config/transmission"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/transmission" target="_blank">transmission wiki</a>  |  
  <a href="https://transmissionbt.com" target="_blank">transmission site</a>
</p>  
