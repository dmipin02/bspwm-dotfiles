# My BSPWM Dotfiles 
This repo includes dotfiles for my bspwm setup 
## Screenshot ![Screenshot](https://i.imgur.com/d03wRBS.png) 

## Installation 

### 1. Install tools (if you dont have) 
``` 
sudo pacman -S picom dunst mpd mpc ncmpcpp ranger rofi 
yay -S polybar 
``` 
##### Note - JetBrains Nerd Font should be installed 

### 2. Clone this repository 
``` 
git clone https://github.com/skalpasi/bspwm-dotfiles 
``` 

### 3. Copy all the files from this repository in your ~/ (home directory) 
#### Note - Make backup or remove your old config files so new config can work smooothly 
``` 
cd bspwm-dotfiles 
cp -r * ~/
``` 

### 4. Reload BSPWM
