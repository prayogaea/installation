# Composer Installation

### Install Composer on Ubuntu, Debian, Kali Linux, and Linux Mint

- Installation
```bash
sudo apt update
```
```bash
sudo apt install php-cli unzip
```
```bash
cd ~
```
```bash
curl -sS https://getcomposer.org/installer -o /tmp/composer-setup.php
```
```bash
HASH=`curl -sS https://composer.github.io/installer.sig`
```
```bash
echo $HASH
```
```bash
php -r "if (hash_file('SHA384', '/tmp/composer-setup.php') === '$HASH') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
```
```bash
sudo php /tmp/composer-setup.php --install-dir=/usr/local/bin --filename=composer
```
```bash
composer
```

- Uninstallation
```bash
sudo apt remove --auto-remove composer
```
```bash
sudo apt purge --auto-remove composer
```
