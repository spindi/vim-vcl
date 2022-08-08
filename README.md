# vim-vcl

A combination of [vcl-vim-plugin](https://github.com/smerrill/vcl-vim-plugin) and [vim-varnish](https://github.com/fgsch/vim-varnish). I preferred the syntax definitions of the former with the ability to fold from the latter.

## Installation

### Using vim-plug

* Add `Plug 'fgsch/vim-varnish'` to `~/.vimrc`
* `:PlugInstall` or `$ vim +PlugInstall +qall`

## Features

### Folding

Setting `g:vcl_fold` enables folding VCL via the syntax engine.
Any block, comment, or inline-C that extends over more than one
line can be folded using the standard Vim and Neovim fold-commands.

This option is off by default.
