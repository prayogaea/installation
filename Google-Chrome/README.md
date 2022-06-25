# Google Chrome Installation

### Install Chrome on Ubuntu, Debian, dan Linux Mint
Open a terminal and use the following command to install Google Chrome on Debian-based Linux distributions, such as Ubuntu, Debian, Kali, and Linux Mint.

- Installation
```bash
sudo apt update
```
```bash
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
```
```bash
sudo apt install ./google-chrome-stable_current_amd64.deb
```
```bash
sudo apt install google-chrome-stable
```

- Uninstallation
```bash
sudo apt remove google-chrome-stable
```
```bash
sudo apt purge google-chrome-stable
```

### Install Chrome on Arch Linux and Manjaro
Open a terminal and use the following command to install Google Chrome on Linux distributions based on Arch Linux, such as Manjaro and Arch Linux.

- Installation
```bash
sudo apt update
```
```bash
git clone https://aur.archlinux.org/google-chrome.git
```
```bash
cd google-chrome
```
```bash
makepkg -s
```
```bash
sudo pacman -U --noconfirm google-chrome-*.xz
```

- Uninstallation
```bash
sudo pacman -R google-chrome
```