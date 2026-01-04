its my hyprland config im currently working at it as a linux newbie

used ItRoy's configs as example
````
git clone https://github.com/Cameroonets/CameroonetsHyprland.git
cd CameroonetsHyprland
cp -r hypr waybar wofi wlogout kitty fish fastfetch ~/.config/
````

нужные пакеты
````
sudo pacman -S wofi kitty swaync brightnessctl freetype2 fish git hyprlock hyprpaper waybar ttf-font-awesome otf-font-awesome ttf-jetbrains-mono pavucontrol feh ranger thunar meson nwg-look papirus-icon-theme fastfetch file powerline-fonts inetutils bluez bluez-utils blueman telegram-desktop vlc fastfetch nerd-fonts grim slurp pipewire font-manager swaybg nftables
````
ttf-nerd-fonts-symbols ttf-nerd-symbols-mono что то из этого я хуй знает
````
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
````
````
yay -S hyprshot wlogout sddm-sugar-candy
````

````
#ПРОСТО ВАЖНЫЕ ПАКЕТЫ ДЛЯ МЕНЯ НЕ СМОТРЕТЬ СЮДА!!!!!!!!!!!!
sudo pacman -S discord steam libreoffice-still libreoffice-still-ru telegram-desktop obs-studio
