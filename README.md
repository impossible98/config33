# Privata Config

## Setup sudo in Debian

```bash
# Log in as root
adduser <username>
apt-get install --no-install-recommends --yes \
    sudo
usermod -aG sudo <username>
```

## Install Node.js

```bash
sudo apt-get install --no-install-recommends --yes \
    curl
curl https://get.volta.sh | bash
source ~/.bashrc
volta install node@lts
volta install yarn
```

## Install Base

```bash
sudo apt-get install --no-install-recommends --yes \
    git
```

## Install oh-my-zsh

```bash
sudo apt-get install --no-install-recommends --yes \
    zsh
```

## Install vim

```bash
sudo apt-get install --no-install-recommends --yes \
    vim
```
