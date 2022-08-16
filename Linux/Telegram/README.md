# Telegram Installation

### Install Telegram on Ubuntu, Debian, Kali Linux, and Linux Mint

- Installation
```bash
sudo apt update
```
```bash
wget -O- https://telegram.org/dl/desktop/linux | sudo tar xJ -C /opt/
sudo ln -s /opt/Telegram/Telegram /usr/local/bin/telegram
```
```bash
telegram &
```

- Uninstallation
```bash
sudo apt remove telegram
```
```bash
sudo apt purge telegram
```