# Voidspin Plymouth Theme

A void linux plymouth theme inspire by spinner theme and this [animation](https://www.reddit.com/r/voidlinux/comments/fyzkjh/made_a_boot_animation_for_voidsplash/).

<img width="800" height="450" alt="demo" src="https://github.com/user-attachments/assets/a5b78804-3fb8-48a3-9c23-5e40c75bf8ff" />

## Installation
1. Copy `./voidspin` folder to `/usr/share/plymouth/themes/`:
```bash
sudo cp -r ./voidspin /usr/share/plymouth/themes/
```
2. Set the theme as default:
```bash
sudo plymouth-set-default-theme -R voidspin
```
