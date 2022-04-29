# dotfiles-dragon
.dotfiles and configs for dragon gaming PC running ArchLinux with X11

**Note:** This is currently heavily in progress.  
For personal use only. Use these files at your own risk.

## Official Packages
- i3-gaps
- i3lock
- rofi
- picom compositor for X11
- ...

## External Packages
- [nerd-fonts-complete](https://aur.archlinux.org/packages/nerd-fonts-complete) - Iconic font aggregator, collection, & patcher. 3,600+ icons, 50+ patched fonts.
- [polybar](https://aur.archlinux.org/packages/polybar) - A fast and easy-to-use status bar
- ...

## symlinks used
```
ln -s /mnt/Work/git/dotfiles-dragon/i3/config ~/.config/i3/config
ln -s /mnt/Work/git/dotfiles-dragon/i3/config.d/10-general.conf ~/.config/i3/config.d/10-general.conf
ln -s /mnt/Work/git/dotfiles-dragon/i3/config.d/20-autostart.conf ~/.config/i3/config.d/20-autostart.conf
ln -s /mnt/Work/git/dotfiles-dragon/i3/config.d/60-workspaces.conf ~/.config/i3/config.d/60-workspaces.conf
ln -s /mnt/Work/git/dotfiles-dragon/i3/config.d/80-keybinds.conf ~/.config/i3/config.d/80-keybinds.conf
ln -s /mnt/Work/git/dotfiles-dragon/i3status/config ~/.config/i3status/config
ln -s /mnt/Work/git/dotfiles-dragon/rofi/config.rasi ~/.config/rofi/config.rasi
ln -s /mnt/Work/git/dotfiles-dragon/picom/picom.conf ~/.config/picom/picom.conf
ln -s /mnt/Work/git/dotfiles-dragon/polybar/config.ini ~/.config/polybar/config.ini
ln -s /mnt/Work/git/dotfiles-dragon/polybar/launch.sh ~/.config/polybar/launch.sh
```
