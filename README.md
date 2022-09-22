# MY NEOVIM CONFIG

This is my neovim config, it's very easy to configure and it has some cool features and custom keymapping.

## Installation

* To install you must have installed some dependencies, such us `nodejs` `npm` `yarn` `fzf` `lua` `curl` 

* Also you will need to install VimPlug 
 ```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
 ```
* Clone the repository into your `.config` folder
```
 git clone https://github.com/apesteguia/nvim.git
```

* If you haven´t already a nvim config folder in your .config, clone this repository in your .config. After that, open neovim and type `:PlugInstall`.

* If you have already a nvim config file and you want to replace it, remove the folder by typing `$ rm -r nvim` and clone the repository afterwards.

* If you want to keep your config, but use this one, you can change the name of your own nvim folder to another one and then clone this repository.  `$ mv /home/user/.config/nvim /home/user/.config/nivm1`.

## Features and COC configuration

### Features
* The main keymap change in this config is the mode change, now you can pass from insert mode to normal mode by typing `jk` or `kj`.
* There are also some customization features such us `airline`, `onedark theme`, `colorizer` and `rainbow-parentheses` installed.
* There is also a `fzf` finder installed.
* If you press `space`, a option menu will apear, in which native explorer and some other userful apps will appaer in choice.

### COC configuration
* With this plugin you can install support for some languages and other useful apps. These are the ones that work with my config. 
`:CocInstall coc-explorer coc-python coc-json coc-lua`.
But you can install much more as it has support for many other programming languages. Get more information at https://github.com/neoclide/coc.nvim



