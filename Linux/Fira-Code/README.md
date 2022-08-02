# Fira Code Installation

### Install [Fira Code](https://github.com/tonsky/FiraCode) on Ubuntu, Debian, Kali Linux, and Linux Mint

- Installation
```bash
sudo apt update
```
```bash
sudo apt install fonts-firacode
```

- Visual Studio Code
> Open vs code then press 
`ctrl+shift+p`
Then look for the open settings json file `Open settings json` and add the following json script.
```json
"editor.fontFamily": "Fira Code",
"editor.fontLigatures": true,
```

- Uninstallation
```bash
sudo apt remove fonts-firacode
```
```bash
sudo apt purge fonts-firacode
```