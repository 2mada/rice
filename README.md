# **/ 2mada's mutter gnome rice**

**/ what is a rice?**
```
“Rice” is a word that is commonly used to refer to making visual improvements and customizations on one’s desktop. 
This is my rice.
```
![image](https://user-images.githubusercontent.com/122813431/218795453-58ac0eff-6071-42a4-9881-2ace47fc9d85.png)

- - - 

**/ apps:**

```
wget https://mullvad.net/download/app/deb/latest/
```

```
sudo apt install neofetch -y && flatpak install flathub io.gitlab.librewolf-community -y && flatpak install flathub com.brave.Browser -y && flatpak install flathub com.spotify.Client -y && flatpak install flathub md.obsidian.Obsidian -y && flatpak install flathub com.mattjakeman.ExtensionManager -y && flatpak install flathub org.flameshot.Flameshot -y && sudo apt-get install virt-manager -y && flatpak install flathub com.discordapp.Discord -y && curl -L https://sw.kovidgoyal.net/kitty/installer.sh | sh /dev/stdin 
```

**for vm:**
```
sudo apt install neofetch -y && flatpak install flathub io.gitlab.librewolf-community -y && flatpak install flathub com.brave.Browser -y && curl -L https://sw.kovidgoyal.net/kitty/installer.sh | sh /dev/stdin && reboot
```

- - - 

**/ theme:**

```
git clone https://github.com/vinceliuice/Colloid-gtk-theme
```

```
cd Colloid-gtk-theme
```

```
./install.sh
```

- - - 

**/ configs:**

**neofetch**
```
cd .config/neofetch
```
```
mv config.conf oldconfig.conf
```
```
cd && git clone https://github.com/oh2porygon/muttergnomerice
```
```
cp muttergnomerice/config.conf ~/.config/neofetch/config.conf
```

**kitty**

```
cd && cp muttergnomerice/kitty.conf ~/.config/kitty/kitty.conf
```

- - - 

**/ icons:**

```
git clone https://github.com/vinceliuice/Tela-circle-icon-theme
```
```
cd Tela-circle-icon-theme
```
```
./install.sh
```

- - - 
**/ font:**
```
wget https://github.com/RedHatOfficial/Overpass/releases/download/3.0.2/overpass-desktop-fonts.zip
```

