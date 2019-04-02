# .dotfiles

## Installation
- This repo uses git submodules, to contain external git projects
```sh
$ git submodule init
$ git submodule update
```
- Install and select the nord theme for your terminal (iterm2 in my case)
- Install and select the powerline fonts
- Install the symlink for the dotfiles contained in this repo
```bash
$ python install.py --config install.yml
```


## Extra steps

```sh
$ cd ~/.vim/bundle/YouCompleteMe
$ ./install.py --clang-completer
```
