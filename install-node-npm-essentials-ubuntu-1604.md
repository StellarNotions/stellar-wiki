# Installing NodeJs, NPM, and Build Essentials on Ubuntu 16.04

## Installing Using a PPA

```bash
cd ~
curl -sL https://deb.nodesource.com/setup_8.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt-get install nodejs -y
sudo apt-get install build-essential -y
```