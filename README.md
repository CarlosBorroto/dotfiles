# dotfiles
My configuration files. Managed with [chezmoi](https://www.chezmoi.io).

## Setup a new machine
### Install required software
* Install [homebrew](https://brew.sh)
* Install 1password: `brew install 1password 1password-cli`
* Install starship: `brew install starship`
* Install chezmoi: `brew install chezmoi`

### Initialize chezmoi
```shell
chezmoi init https://github.com/CarlosBorroto/dotfiles.git
chezmoi apply
```
