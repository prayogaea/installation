# Xampp Installation

### Install Xampp on Ubuntu, Debian, Kali Linux, and Linux Mint

- Installation
    Download the XAMPP package from the official website [XAMPP](https://www.apachefriends.org/index.html)

    > Customize xampp package version

```bash
cd Downloads
```
```bash
sudo chmod 755 xampp-linux-x64-8.1.6-0-installer.run
```
```bash
ls -l xampp-linux-x64-8.1.6-0-installer.run
```
```bash
sudo ./xampp-linux-x64-8.1.6-0-installer.run
```
- Permision htdocs
```bash
sudo chmod -R 777 /opt/lampp/htdocs/
```

- Open the window
```bash
sudo /opt/lampp/manager-linux-x64.run
```

- Open a browser window
```bash
http://localhost/dashboard/
```
```bash
http://localhost/dashboard/phpinfo.php
```
```bash
http://localhost/phpmyadmin/
```

- Uninstallation
```bash
sudo /opt/lampp/uninstall
```
```bash
sudo rm -r /opt/lampp
```