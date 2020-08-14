# Environnement de bureau

## Screenshots



## Installation

### i3wm-gaps
```bash
# Ajout du PPA
sudo add-apt-repository ppa:kgilmer/speed-ricer
sudo apt-get update

# Installation du fork d'I3Wm
sudo apt install i3wm-gaps

# Ecriture de la config dans le fichier ~/.config/i3/config
cat ./configs/i3/config > ~/.config/i3/config
```

Modifiez le fichier i3/config en, fonction de votre configuration vidéo. Pour connaitre le nom de vos sorties vidéos, exécutez `xrandr`. Cet outil vous permet aussi de changer la disposition de vos écrans


### Rofi
```bash
sudo apt install rofi

# Installation du theme slate
cp ./configs/rofi/slate.rasi /usr/share/rofi/themes

# Ecriture de la config dans le fichier ~/.config/rofi/config
cat ./configs/rofi/config > ~/.config/rofi/config
```

### Polybar
```bash
sudo apt install fonts-font-awesome

# Ecriture de la config dans le fichier ~/.config/i3/config
cat ./configs/polybar/config > ~/.config/polybar/config
```