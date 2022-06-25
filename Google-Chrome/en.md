# Google Chrome Installation

### Install Chrome on Ubuntu, Debian, Kali Linux, and Linux Mint

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