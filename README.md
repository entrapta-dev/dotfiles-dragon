# dotfiles-dragon
.dotfiles and configs for dragon gaming PC running ArchLinux with X11

**Note:** This is currently heavily in progress.  
For personal use only. Use these files at your own risk.

## Official Packages
- i3-gaps
- i3lock
- i3status
- rofi
- ...

## External Packages
- [nerd-fonts-complete](https://aur.archlinux.org/packages/nerd-fonts-complete) - Iconic font aggregator, collection, & patcher. 3,600+ icons, 50+ patched fonts.
- ...

## symlinks used
```
ln -s /mnt/Work/git/dotfiles-dragon/i3/config ~/.config/i3/config
ln -s /mnt/Work/git/dotfiles-dragon/i3/config.d/10-general.conf ~/.config/i3/config.d/10-general.conf
ln -s /mnt/Work/git/dotfiles-dragon/i3/config.d/60-workspaces.conf ~/.config/i3/config.d/60-workspaces.conf
ln -s /mnt/Work/git/dotfiles-dragon/i3/config.d/80-keybinds.conf ~/.config/i3/config.d/80-keybinds.conf
```
