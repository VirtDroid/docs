# Aur helpers installation
It is possible to install an AUR (Arch User Repository) Helper on those VMs. I recommend using the [Setup Script](https://github.com/VirtDroid/easybuild) to setup firefox and an aur helper. To manually install a helper, you can:
1. Setup with the autosetup and install the helper from the paru
2. Use a PKGbuild (instructions below for most common ones)

## Installing yay
First, install the base packages with
``` sh
pacman -S --needed base-devel
pacman -S kernel26-headers file base-devel abs git
```
Then install the aur helper with 
``` sh
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
cd ..
```
you can now search packages with yay -Ss <pkg> and install them
## Installing paru
First, install the base packages with
``` sh
pacman -S --needed base-devel
pacman -S kernel26-headers file base-devel abs git
```
Then install the aur helper with 
``` sh
git clone https://aur.archlinux.org/paru.git
cd paru
makepkg -si
cd ..
```
you can now search packages with paru search <pkg> and install them