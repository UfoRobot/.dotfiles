# .dotfiles

## Installation
- This repo uses git submodules, to contain external git projects
```sh
$ git submodule init
$ git submodule update
```
- Install and select the nord theme for your terminal (iterm2 in my case)
- Install and select the powerline fonts
- Create folders for swap files and persistent undos in vim
```sh
mkdir ~/.vim/tmp
mkdir ~/.vim/tmp/swap
mkdir ~/.vim/tmp/backup
mkdir ~/.vim/tmp/undo
```
- Install the symlink for the dotfiles contained in this repo, you can see a list of the 
installed symlinks in the configuration yml
```bash
$ python install.py --config install.yml
```
- Enter tmux and install the tmux plugins
```bash
$ tmux
$ <crtl> + b I
```
- Make sure you have system python in your path, and install the vim plugins (YouCompleteMe requires 
being installe with system python)
```bash
$ vim 
$ cd ~/.vim/bundle/YouCompleteMe
$ ./install.py --clang-completer
```

## Reading list
- [Why do Vim experts prefer buffers over tabs?](https://stackoverflow.com/questions/26708822/why-do-vim-experts-prefer-buffers-over-tabs)
- [Buffers, Windows, Tabs... Oh My! Part 1: Vim Buffers](https://dockyard.com/blog/2013/10/22/vim-buffers)
