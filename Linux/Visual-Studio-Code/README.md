# Visual Studio Code Installation

### Install Visual Studio Code on Ubuntu, Debian, Kali Linux, and Linux Mint

- Installation
```bash
sudo apt update
```
```bash
sudo apt install software-properties-common apt-transport-https wget -y
```
```bash
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
```
```bash
sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
```
```bash
sudo apt install code
```
```bash
code
```

- Uninstallation
```bash
sudo apt remove code
```
