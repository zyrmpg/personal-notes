XPS13 Fedora
============

Install
-----------
 - Google Chrome

 `curl https://dl.google.com/linux/direct/google-chrome-stable_current_x86_64.rpm`

 `dnf install google-chrome-stable_current_x86_64.rpm`

 - Atom

 `dnf install $(curl -sL "https://api.github.com/repos/atom/atom/releases/latest" | grep "https.*atom.x86_64.rpm" | cut -d '"' -f 4)`

 - Deluge

 `dnf install deluge`
 - Remarkable

 ` sudo dnf install webkitgtk3.x86_64 and sudo dnf install gtksourceview3`

 [https://remarkableapp.github.io/files/remarkable-1.87-1.rpm](https://remarkableapp.github.io/files/remarkable-1.87-1.rpm)


//adobe-source-code-pro-fonts


~/.config/
-------

 - autostart/*

 - Code/User/settings.json

 - nemo/*

 - rofi/config

 - terminator/config

 - user-dirs.dirs

 - mimeapps.list


/usr/share/applications/\*.desktop
--------------

 - spotify

 - code


Misc.
-----
 - Set deluge as magnet handler

 `x-scheme-handler/magnet=deluge.desktop >> ~/.config/mimeapps.list`

 - Set font mono dejavu


 https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/


guake prefs
