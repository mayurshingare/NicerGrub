# NicerGrub
Nicer Theme for GRUB using JetBrains Mono Font and a dark background. Built and tested on Arch Linux.

- [Screenshots](#Screenshots)
- [Installation](#Installation)
- [Credits](#Credits)

## Screenshots
![NicerGrub Home Screen](https://github.com/mayurshingare/NicerGrub/blob/main/screenshots/nicergrub-home.png)
![NicerGrub Terminal Screen](https://github.com/mayurshingare/NicerGrub/blob/main/screenshots/nicergrub-terminal.png)

## Installation
1. Copy the NicerGrub directory to /boot/grub/themes/
```bash
sudo cp -r Downloads/NicerGrub /boot/grub/themes
```
2. Edit /etc/default/grub to use the NicerGrub theme
```bash
sudoedit /etc/default/grub
```
3. Update the GRUB_THEME line to point to the installed NicerGrub theme
```vi
GRUB_THEME="/boot/grub/themes/NicerGrub/theme.txt"
```
4. Regenerate the grub.cfg file
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```
5. Reboot

## Credits
- [free background photos from pngtree.com](https://pngtree.com/free-backgrounds)
- [JetBrains Mono Font](https://www.jetbrains.com/lp/mono/)
- [grub2-theme-preview](https://pypi.org/project/grub2-theme-preview/)
