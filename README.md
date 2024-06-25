# My dotfiles
This directory contains the dotfiles for my system

## Requirements
Ensure you have the following installed on your system

### Git
```
pacman -S git
```

### Stow
```
pacman -S stow
```

## Installation
Check out the dotfiles repo in your $HOME directory using git
```
$ git clone git@github.com/amidonc/dotfiles.git

$ cd dotfiles
```

then use GNU stow to create symlinks
```
$ stow .
```
