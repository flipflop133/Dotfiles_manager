# DOTFILES BACKUP UTILITY
------
## Features:
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-backup and restore all your dotfiles
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-support white spaces in paths
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-backup manually installed packages
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-push dotfiles to your repo
------
## How to use:
### Backup:
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Simply the path of your dotfile(directory or file) in "dotfiles_list.txt" as follow:
###### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; eg: "/home/yourusername/.config/magicWM/config"
###### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    -> ".config/magicdotfile"
###### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (So no need to add your home path.)
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Run the script in your terminal:
###### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $ ./backup.sh
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To push the dotfiles to your dotfile repo, copy backup.sh and dotfiles_list.txt to your repo directory.
### Restore:
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Clone your dotfile backup repository.
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Put the backup.sh and dotfiles_list.txt files inside your cloned repository.
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Run the script in your terminal:
###### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $ ./backup.sh
###### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Select restore(2) and your are done!
------
### Feel free to do pull requests ;)
------
### Thanks to [Mortezadadgar](https://github.com/mortezadadgar) for his help and feedbacks on this script!
