# .dotfiles

## Project Goal
Personal dotfiles configuration repository for managing shell environment configurations across systems.

## Usage
This repository contains various shell configuration files:

- `.bashrc` - Main Bash configuration file
- `.bash-alias` - Custom Bash aliases
- `.docker-alias` - Docker-specific aliases

### Installation
Clone this repository and symlink the desired configuration files to your home directory:

```bash
git clone https://github.com/aagret/.dotfiles.git
ln -s ~/.dotfiles/.bashrc ~/.bashrc
ln -s ~/.dotfiles/.bash-alias ~/.bash-alias
ln -s ~/.dotfiles/.docker-alias ~/.docker-alias
```

Source the updated configuration:
```bash
source ~/.bashrc
```