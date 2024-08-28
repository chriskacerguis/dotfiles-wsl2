# dotfiles

My dotfiles for WSL2 (Ubuntu).

## Installation

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```shell
eval "$(/opt/homebrew/bin/brew shellenv)"
```

```shell
brew install dotbot
```

```shell
git clone https://github.com/chriskacerguis/dotfiles-wsl2.git ~/.dotfiles
```

```shell
dotbot -d ~/.dotfiles -c ~/.dotfiles/install.conf.yaml 
```