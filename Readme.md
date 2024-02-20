# The cat dotfiles on Windows

## Installation

- Install MSYS2
- Install stow on MSYS2
```sh
pacman -S stow
```
- Modify your environment to have MSYS=winsymlinks:nativestrict
- Open MSYS prompt and run
```sh
stow . -t /c/Users/<username>
./install-scripts/deploy-starship.sh 
./install-scripts/deploy-nvim.sh 
```

