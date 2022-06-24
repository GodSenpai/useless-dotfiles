# useless-dotfiles
My dotfiles for themes. I didnt make the polybar themes
*Before you start: Unzip totally-my-dotfiles.zip and put the folder in your home dictonary*

Whats needed before installation:

- bspwm: https://github.com/baskerville/bspwm (Can be installed with package manager)

- polybar: https://github.com/polybar/polybar (Can be installed with package manager)

- pywal: https://github.com/dylanaraps/pywal (Can be installed with package manager on arch. Dunno about ubuntu or Fedora)

- sxhkd: https://github.com/baskerville/sxhkd (Can be installed with package manager on arch. Dunno about ubuntu or Fedora)
- lxappearence

- zsh and Oh-My-Zsh: https://github.com/ohmyzsh/ohmyzsh

- power10k zsh theme (I recomend you to  configure this on your own): https://github.com/romkatv/powerlevel10k

- dunst (Can be installed on Arch with pacman. Dunno about Ubuntu or Fedora)

# Since the installation folder is in my totally-my-dotfiles, all you have to do is refer to line 80 and 81 to install this.
- Distrotube color scripts alredy installed: https://gitlab.com/dwt1/shell-color-scripts

- Nitrogen


Scroll to the end use just the commands

__________________________________
Bspwm Configurations and Keyblinds:

1.Git  Clone my file (totally my dotfliles). You can do this by doing:
git clone https://gitlab.com/Siurzu/totally-my-dotfiles.git

After you do that you first want to copy my bspwmrc to your own. Your bspwm rc could be located at: ~/.config/bspwm. 

Once you do that copy my keyblinds (at sxhkdrc) to yours (which'll be in the same folder). Again your sxhkdrc should be in: ~/.config/sxhkd

After you do that you should have my keyblinds and also my bspwm configuration,
____________________________________________________________________________________________________
Polybar: 

I got my polybar configuration from: https://github.com/adi1090x/polybar-themes. I did not make that polybar themes nor do I own it. 
I use grayblocks theme, although you may change it. If you do so happen to change it go to my bspwmrc and change the end of line 11 and change grayblocks to whatever polybar theme you choose.
___________________________________________________________________________________________________

Zsh theme and Configuration:

Copy my .zshrc to your own zshrc, and my p10k.zsh to your own. Also read the README file in it.
____________________________________________________________________________________________________

Neofetch and Dunst:

Copy my neofetch.conf to your own. Your neofetch defalut configuration should be locatd at 
~/.config/neofetch.

Do the same thing for Dunst. Your dunst configuration should be located at ~/.config/dunst.
________________________________________________________________________________________________

Gtk Theme and Rofi:

I use the Fluent Gtk theme. Just follow the installation for it at: https://github.com/vinceliuice/Fluent-gtk-theme.

Or you can copy whats in Gtk Theme folder (in totally my dotfile) and copy to ~/.themes/. And change it with lxappearence.

Rofi:
For rofi I use the catppuccin theme. Just copy the catppuccin.rasi theme to wherever your rofi themes are stored, which should be:
_________________________________________________________________________________

Commands:

Before you start: Unzip totally-my-dotfiles.zip and put the folder in your home dictonary 

cp ~/totally-my-dotfiles/Bspwm and Sxkhd Configs/bspwmrc ~/.config/bspwm/bspwmrc
cp ~/totally-my-dotfiles/Bspwm and Sxkhd Configs/sxhkdrc ~/.config/sxhkd/sxhkdrc
cp ~/totally-my-dotfiles/polybar ~/.config/polybar
cp ~/totally-my-dotfiles/Gtk Themes/darknord-gtk-theme ~/.themes/
(If themes isn't already a file do: mkdir ~/.themes/ After that change your gtk-theme in appearence)
cp ~/totally-my-dotfiles/Neofetch Config/config.conf ~/.config/neofetch/config.conf
cp ~/totally-my-dotfiles/dunst/dunstrc ~/.config/dunst/dunstrc
cd ~/totally-my-dotfiles/Distrotube's Terminal Color Scripts/shell-color-scripts
zsh (or bash depending on what you use) ./colorscripts.sh

#To get Catppuccin Rofi Theme
Follow: https://github.com/catppuccin/rofi

git clone https://github.com/catppuccin/rofi ./.catppuccin-rofi
cd ./.catppuccin-rofi
mkdir -p ~/.config/rofi ~/.local/share/rofi/themes
cp -r ./.config/rofi/* ~/.config/rofi
cp -r ./.local/share/rofi/themes/* ~/.local/share/rofi/themes/

Run rofi-theme-selector in the terminal and pick the catppuccin theme with crtl + a
______________________________________________________________________________________
