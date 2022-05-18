# Configs

### Current Setup
![image](https://user-images.githubusercontent.com/56120837/169096841-467f4e6c-a882-4d34-be1d-91b5bd251b73.png)

#### Focused window title
![image](https://user-images.githubusercontent.com/56120837/169097090-b69a86b2-ce56-4b7a-a7d1-6c547e4bac32.png)


### i3wm

#### Install these packages
- i3-gaps - tiling window manager
- rofi - application menu
- nitrogen - desktop background manager
- i3blocks - i3status bar (v >= 1.5.0)
- i3blocks-modules - various modules for i3blocks


### Install i3blocks (v 1.5.0)
```bash
apt cache search dh-autoreconf
apt install dh-autoreconf
apt install make
git clone https://github.com/vivien/i3blocks
cd i3blocks
chmod +x autogen.sh
./autogen.sh
./configure
make
make install
```

### Install i3blocks-modules
```bash
git clone https://github.com/cytopia/i3blocks-modules.git
cd i3blocks-modules
make install
```

### Themes
- [Arc-Darkest-3.38](https://www.xfce-look.org/p/1317409) - Endeavour OS

### Icons
- [Papirus](https://www.xfce-look.org/p/1166289)
- [Qogir](https://www.xfce-look.org/p/1296407/) - Endeavour OS

### Cursors
- [WhiteSur](https://www.xfce-look.org/p/1411743)

### Fonts
- [FiraCode Nerd font](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/FiraCode/Regular/complete) (Regular, SemiBold, Bold)
