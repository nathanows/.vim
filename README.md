.vim
====

My vim dot files. the `.vimrc` file is saved to [vimrc](https://github.com/nathanows/.vim/blob/master/vimrc).

**Table of Contents**

<!-- toc -->

- [About](#about)
  * [Installing](#installing)
  * [Pathogen](#pathogen)
- [Contributing](#contributing)
  * [Using the `Makefile`](#using-the-makefile)
- [Plugins Used](#plugins-used)

<!-- tocstop -->

## About

### Installing

Just run the following commands via terminal to get perfectly set up:

```console
$ cd ~/
$ git clone --recursive https://github.com/nathanows/.vim.git .vim
$ ln -sf $HOME/.vim/vimrc $HOME/.vimrc
$ cd $HOME/.vim
$ git submodule update --init
```

### Pathogen
The vim dot files make use of the excellent [Pathogen](https://github.com/tpope/vim-pathogen) runtime path manager to install plugins and runtime files into their own private directiories.

Currently using version 2.4 of Pathogen

## Contributing

### Using the `Makefile`

You can use the [`Makefile`](Makefile) to run a series of commands.

```console
$ make help
install                        Sets up symlink for user and root .vimrc for vim and neovim.
README.md                      Generates and updates plugin info in README.md.
remove-submodule               Removes a git submodule (ex MODULE=bundle/nginx.vim).
update                         Updates all plugins.
```

## Plugins Used
* [github.com/sjl/badwolf](https://github.com/sjl/badwolf.git)
* [github.com/RyanMillerC/better-vim-tmux-resizer](https://github.com/RyanMillerC/better-vim-tmux-resizer.git)
* [github.com/ctrlpvim/ctrlp.vim](https://github.com/ctrlpvim/ctrlp.vim.git)
* [github.com/Yggdroot/indentLine](https://github.com/Yggdroot/indentLine.git)
* [github.com/itchyny/lightline.vim](https://github.com/itchyny/lightline.vim.git)
* [github.com/preservim/nerdtree](https://github.com/preservim/nerdtree.git)
* [github.com/Xuyuanp/nerdtree-plugin.git](https://github.com/Xuyuanp/nerdtree-git-plugin.git)
* [github.com/codota/tabnine-vim](https://github.com/codota/tabnine-vim.git)
* [github.com/ntpeters/vim-better-whitespace](https://github.com/ntpeters/vim-better-whitespace.git)
* [github.com/tpope/vim-endwise](https://github.com/tpope/vim-endwise.git)
* [github.com/tpope/vim-five.git](https://github.com/tpope/vim-fugitive.git)
* [github.com/tpope/vim.git](https://github.com/tpope/vim-git.git)
* [github.com/airblade/vimgutter.git](https://github.com/airblade/vim-gitgutter.git)
* [github.com/fatih/vim-go](https://github.com/fatih/vim-go.git)
* [github.com/elzr/vim-json](https://github.com/elzr/vim-json.git)
* [github.com/tpope/vim-pathogen](https://github.com/tpope/vim-pathogen.git)
* [github.com/uarun/vim-protobuf](https://github.com/uarun/vim-protobuf.git)
* [github.com/tpope/vim-sensible](https://github.com/tpope/vim-sensible.git)
* [github.com/tpope/vim-surround](https://github.com/tpope/vim-surround.git)
* [github.com/christoomey/vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator.git)
* [github.com/stephpy/vim-yaml](https://github.com/stephpy/vim-yaml.git)
