# NVIM config
A backup of a very basic but usuable neovim config.
This repo is a message to future me if I ever need to re-setup

## Prerequisities
- Terminal setup, im using [iTerm2](https://iterm2.com/downloads.html).
- Custom Font, [Cousine Nerd Font for now](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.1.1/Cousine.zip) contains icons for neo-tree

## Setup
- OSX
`git clone https://github.com/danpierce1/nvim-config.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim`
- Windows (/w powershell)
`git clone https://github.com/danpierce1/nvim-config.git $env:USERPROFILE\AppData\Local\nvim\`

## Start Neovim
- `nvim`
- `PackerSync` to install plugins

## Adding new Plugins
- Add import to "lua/dpierce/packer.lua"
- Create new config file in "after/plugin" and configure as required
- `so` the files
- `PackerSync` to install

## Keybinds
- `<space><tab>` to access neo-tree
- arrows to navigate
- `<enter>` to access
- `?` for more
- `<space>/` to search open files
- `<space>sf` to search files
- `<space>sg` to search with grep
- `<space>a` to add current file to harpoon quicklist
- `Ctrl e` to access quick list
- more in "lua/dpierce/remap.lua"
