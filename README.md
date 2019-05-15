# Recommended Installation
`sudo apt-get install curl`
`sh -c "$(curl https://raw.githubusercontent.com/benchillingt/setup_new_vm/master/setup.sh)"`

## setup.sh
script to run on new Ubuntu 18.04 installation:
  - installs decent dotfiles (per this repo)
  - installs oh-my-zsh & some decent themes
  - installs i3

## dotfiles
dotfiles basic install & update via the Makefile

### install
`make` or `make all`

### update local repo files from your active dotfiles in your ~/ directory
`make update`

