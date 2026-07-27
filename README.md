# Voidspin Plymouth Theme

A void linux plymouth theme inspire by spinner theme and this [animation](https://www.reddit.com/r/voidlinux/comments/fyzkjh/made_a_boot_animation_for_voidsplash/).

<img width="1920" height="1080" alt="demo" src="https://github.com/user-attachments/assets/8f1381f9-4923-4642-825d-0d49c9f42282" />

## Installation]
1. Copy `./voidspin` folder to `/usr/share/plymouth/themes/`:
```bash
sudo cp -r ./voidspin /usr/share/plymouth/themes/
```
2. Set the theme as default:
```bash
sudo plymouth-set-default-theme -R voidspin
```
