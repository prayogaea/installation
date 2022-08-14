# C Installation

### Install C on Ubuntu, Debian, Kali Linux, and Linux Mint

- Installation
```bash
sudo apt update
```
```bash
sudo apt install build-essential
```
```bash
sudo apt-get install manpages-dev
```
```bash
gcc --version
```
> Output
```bash
gcc (Debian 11.2.0-10) 11.2.0
Copyright (C) 2021 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
```

- Test Installation
```bash
nano hello.c
```
```c
#include <stdio.h>
int main()
{
  printf ("Hello, World!\n");
  return 0;
}
```
```bash
gcc hello.c -o hello
```
```bash
./hello
```
> Output
```bash
Hello, World!
```

- Uninstallation
```bash
sudo apt remove build-essential
```
```bash
sudo apt-get purge build-essential
```
```bash
sudo apt-get remove manpages-dev
```
```bash
sudo apt-get purge manpages-dev
```
```bash
sudo apt-get remove gcc
```
```bash
sudo apt-get purge gcc
```