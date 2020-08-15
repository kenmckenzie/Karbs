# Ken's port of (LARBS) which deploy's my own dotfiles (karbs, get it..... :) )

This is a edited fork of LARBS from https://github.com/lukesmithxyz which deploy's my own dotfiles based on qtile window manager with
custom forks of both st and dmenu, it strives to provide a keyboard centric desktop workflow that can also be mouse 
driven when the need arises (I do not believe in making my system obtuse for the sake of it)

# Installation instructions
Simple, clone the repo and run karbs.sh on a freshly installed Arch Linux(With networking enabled!) . Once complete boot into qtile and run setbg in terminal to set 
the colorscheme to the default wallpaper(or you are welcome to use another as an argument to the script)

# Usage

For the purposes of the desktop, Mod = the windows key
Capslock is reassigned to escape with a single press and a mod key when held down
Workspaces are accessed using Mod + 1-9 
Mod + enter = start terminal(default my custom st)
Mod + q = close active window
Mod + space = turns active window floating
Mod + F1 = Start Atom Text editor
Mod + F2 = Start Brave Browser
Mod + F3 = Start Thunar File Manager
Mod + shift + F3 = same as above but root
Mod + 0 = Logout,poweroff,restart dmenu.
Mod + d = Dmenu for launching apps

Please refer to the qtile config for the rest

# Credits
Huge thanks to Luke Smith who saved me a ton of time implementing this myself. Please support him if you
find this usefull


Only testing for now, installation works but still alot of manual tweaking needed to be done
