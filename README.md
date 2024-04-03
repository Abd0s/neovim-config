# Neovim configurations

This repository contains my neovim configurations.

## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

Linux
```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```

Powershell
```Powershell
Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak
Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak
```

#### Clone the repository

Linux
```shell
git clone https://github.com/Abd0s/neovim-config.git ~/.config/nvim
```

Powershell
```Powershell
git clone https://github.com/Abd0s/neovim-config.git $env:LOCALAPPDATA\nvim
```

#### Start Neovim

```shell
nvim
```
# neovim-config
