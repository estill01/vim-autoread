# vim-autoread
> Updated fork of https://github.com/djoshea/vim-autoread, which is itself
> a bundled form of this [script][1], now made fetchable by the [vim-plug][2] plugin manager.

Automatically refreshes content displayed in vim / neovim files when they're changed by other users / processes. 
Useful if you want to e.g. generate code in one process and edit the file directly in another. 


## Installation

Get set up with the fantastic `vim-plug` vim plugin manager:
https://github.com/junegunn/vim-plug


Then place this in `.vimrc` or e.g. `~/.config/nvim/init.vim` if you're using NeoVim:
```
call plug#begin()
Plug 'estill01/vim-autoread'
call plug#end()
```

Then run in vim / neovim:
```
:PlugInstall
```

Open a new buffer and you're all set! 

[1]: http://vim.wikia.com/wiki/Have_Vim_check_automatically_if_the_file_has_changed_externally
[2]: https://github.com/junegunn/vim-plug

