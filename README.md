# Neovim-Plugins
Neovim configurations for support autocomplete and language server for solidity and python


Clone the repo into .config/nvim
Then nvim.init and `:PlugInstall`
Moreover, to support python language server you need to run the following
`apt install nodejs`

`apt install npm -g`

`cd ~/.local/share/nvim/plugged/coc.nvim`

`yarn install`

`yarn build`

then you need to install jedi language server for nvim to support python autocomplete

`pip3 install jedi`

if everything works fine you should see something like this

![alt text](https://raw.githubusercontent.com/MohamedFawzy/Neovim-Plugins/main/nvim.jpg)

