## dotfiles
A simple repo to store dotfiles and other configuration used when developing on MacOS.

### Pre requisites
- [Homebrew](https://brew.sh/)
- [oh-my-zsh](https://ohmyz.sh/#install)
- [GNU stow](http://formulae.brew.sh/formula/stow#default)

### Instructions
1. Clone this repo into the home directory after installing the pre-requisites.
2. run `stow .` from inside the dotfiles repo to create symlinks in the home directory.
3. Remove any wanted depdendencies from the [Brewfile](Brewfile) and run `brew bundle install` to install eveything from the contents of the Brewfile.