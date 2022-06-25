# Pemasangan Google Chrome

### Instal Chrome di Ubuntu, Debian, Kali Linux, dan Linux Mint
Buka terminal dan gunakan perintah berikut untuk menginstal Google Chrome pada distribusi Linux berbasis Debian, seperti Ubuntu, Debian, Kali Linux, dan Linux Mint.

- Instalasi
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

- Penghapusan instalasi
```bash
sudo apt remove google-chrome-stable
```
```bash
sudo apt purge google-chrome-stable
```

### Instal Chrome di Arch Linux dan Manjaro
Buka terminal dan gunakan perintah berikut untuk menginstal Google Chrome pada distribusi Linux berbasis Arch Linux, seperti Manjaro dan Arch Linux.

- Instalasi
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

- Penghapusan instalasi
```bash
sudo pacman -R google-chrome
```