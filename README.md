# DOTFILES MANAGER UTILITY
------
## Features:
* Backup and restore all your dotfiles.
* Backup and restore all your system files.
* Backup manually installed packages.
* push dotfiles to your repo
* White spaces in paths are supported.
------

## How to use:

### Backup:
#### Dotfiles
>**Simply put all the paths of your dotfiles(directories or files) in "dotfiles_list.txt" as follow:**
*dotfiles_list.txt:*
```bash
.config/polybar
.config/nvim/init.vim
```
(No need to add your home path.)
**Run the script in your terminal:**
```bash
$ ./dotfiles_manager.sh
```
#### System files
>**Simply put all the paths of your system files(directories or files) in "system_files.txt" as follow:**
*system_files.txt:*
```bash
/etc/lightdm
/etc/fstab
```
**Run the script in your terminal:**
```bash
$ ./dotfiles_manager.sh
```

### Restore:
>Clone your dotfile backup repository.

#### Dotfiles
>**Put the dotfiles_manager.sh and dotfiles_list.txt files inside your cloned repository.
Run the script in your terminal:**
```bash
$ ./dotfiles_manager.sh
```

#### System files
>**Put the dotfiles_manager.sh and system_files.txt files inside your cloned repository.
Run the script as root in your terminal:**
```bash
$ ./dotfiles_manager.sh
```

------
### Feel free to do pull requests ;)
------
>Thanks to [Mortezadadgar](https://github.com/mortezadadgar) for his help and feedbacks on this script!
