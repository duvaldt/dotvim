# My vim configuration

This is how I have vim configured

## Installation

> cd # go to your home folder <br/>
> git clone git@github.com:/duvaldt/dotvim.git ~/.vim # clone repo into .vim

## Create symlinks

> ln -s ~/.vim/vimrc ~/.vimrc <br/>
> ln -s ~/.vim/gvimrc ~/.gvimrc

## Switch to the `~/.vim` directory, and fetch submodules

> cd ~/.vim <br/>
> git submodule init <br/>
> env GIT_SSL_NO_VERIFY=true git submodule update

## Install dependencies

> sudo apt-get install exuberant-ctags

## Update bundles

> git submodule foreach git pull origin master
