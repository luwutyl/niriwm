# niriwm
My dotfiles aren't a ready-made solution; you'll need some level of familiarity with Niri and Linux. You'll need to dig into the dotfiles and remove or change everything to suit your needs, as this is literally the system I use. Think of it as a partially configured system that needs some tweaking. If you have any questions, just post an issue; I'll help with anything.

## Dependencies
### aur
niri-wip-git

### pacman 
hyprlock \
hypridle \
rofi(https://github.com/adi1090x/rofi) \
waybar \
cava \
swaync \
swww-daemon \
swaybg \
pavucontrol \
btop \
stow \
ranger

## Installation
1. Create a folder ".dotfiles" in your home directory.

`cd` \
`mkdir .dotfiles` \
`cd .dotfiles`

2. Clone the repository

`git clone https://github.com/luwutyl/niriwm.git`

3. Download dependencies(be sure to install https://github.com/adi1090x/rofi)
4. Remove the readme
 
`rm -rf README.md`

5. Using the stow utility, you will need to create symbolic links to your config directories, but first delete all files and folders in the home directory and in the .config folder that are in the .config folder of my repository. The list of commands is below. (When you delete the Niri config, the window manager will forget its settings. It's better to install it in a tty.)

`rm -rf ~/.zshrc` \
`rm -rf ~/.config/eww` \
`rm -rf ~/.config/fastfetch` \
`rm -rf ~/.config/hypr` \
`rm -rf ~/.config/kitty` \
`rm -rf ~/.config/niri` \
`rm -rf ~/.config/ranger` \
`rm -rf ~/.config/rofi` \
`rm -rf ~/.config/waybar` \

`cd ~/.dotfiles` \
`stow .` \

6. open niri

`niri-session`

## Key Bindings

in development
