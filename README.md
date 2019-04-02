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
mkdir .vim/tmp/swap
mkdir .vim/tmp/backup
mkdir .vim/tmp/undo
```
- Install the symlink for the dotfiles contained in this repo
```bash
$ python install.py --config install.yml
```


## Extra steps

```sh
$ cd ~/.vim/bundle/YouCompleteMe
$ ./install.py --clang-completer
```
