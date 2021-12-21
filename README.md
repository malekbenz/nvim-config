# nvim-config
## Configuration
### Where to put the configuration file?
First of all, the neovim config file is named init.vim regardless of your system.

Second, based on Neovim official documentation, you should put init.vim under the directory `~/AppData/Local/nvim` on Windows. To find here that directory is exactly, use the command 
`echo stdpath('config')` inside Neovim.
If this directory does not exist, do not worry. Just create it and put your config file there.

### Install plugin-manager vim-plug
vim-plug is popular plugin manager for Neovim. To install it on Windows, open a PowerShell terminal (not Windows CMD!), and execute the following command:
```
md ~\AppData\Local\nvim\autoload
```

Dowload [autoload/plugvim](autoload/plug.vim)

Download init.vim, use the following settings for vim-plug:
[init.vim](./init.vim)

When we run command `:PlugInstall`, all the plugins will be installed under `~/AppData/Local/nvim/plugged`. We can also change this directory to where we want, for example, `~/AppData/Local/nvim-data/plugged`.