# Pemasangan Visual Studio Code

### Instal Visual Studio Code di Ubuntu, Debian, Kali Linux, dan Linux Mint

- Instalasi
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

- Penghapusan instalasi
```bash
sudo apt remove code
```
