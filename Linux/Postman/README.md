# Postman Installation

### Install Postman on Ubuntu, Debian, Kali Linux, and Linux Mint

- Installation
    Download the Postman package from the official website [Postman](https://www.postman.com/downloads/) 
    
    > [Download](https://dl.pstmn.io/download/latest/linux64) Latest Version

    > Customize postman package version

```bash
cd Downloads
```
```bash
tar -xvf postman-linux-x64.tar.gz
```
```bash
sudo mkdir -p /opt/apps/
```
```bash
sudo mv Postman /opt/apps/
```
```bash
sudo ln -s /opt/apps/Postman/Postman /usr/local/bin/postman
```

- Open the window
```bash
postman
```

> To start the app from a launcher icon, you need to create a .desktop file (a shortcut that is used to launch an application in Linux) for Postman desktop app and save it in the following location.

```bash
sudo vim /usr/share/applications/postman.desktop
```
```bash
[Desktop Entry]
Type=Application
Name=Postman
Icon=/opt/apps/Postman/app/resources/app/assets/icon.png
Exec="/opt/apps/Postman/Postman"
Comment=Postman Desktop App
Categories=Development;Code;
```

- Uninstallation
```bash
sudo rm -rf /opt/apps/Postman && rm /usr/local/bin/postman
```
```bash
sudo rm /usr/share/applications/postman.desktop
```