# MY NEOVIM CONFIG

This is my neovim config, it's very easy to configure and it has some cool features and custom keymapping.

## Installation
  
* If you haven´t already a nvim config folder in your .config, clone this repository in your .config. After that, open neovim and type `:PlugInstall`.

* If you have already a nvim config file and you want to replace it, remove the folder by typing `$ rm -r nvim` and clone the repository afterwards.

* If you want to keep your config, but use this one, you can change the name of your own nvim folder to another one and then clone this repository. 
You can rename the folder by typing `$ mv /home/user/.config/nvim /home/user/.config/nivm1`.

## Features and COC configuration

### Features
* The main keymap change in this config is the mode change, now you can pass from insert mode to normal mode by typing `jk` or `kj`.
* There are also some customization features such us `airline`, `onedark theme`, `colorizer` and `rainbow-parentheses` installed.
* There is also a `fzf` finder installed.
* If you press space, a option menu will apear, in which native explorer and some other userful apps will appaer in choice.

### COC configuration
* With this plugin you can install support for some languages and other useful apps. These are the ones that work with my config. `:CocInstall coc-explorer coc-python coc-json coc-lua coc-vim`.
 But you can install much more as it has support for many other programming languages.



