How to Install VIM-PHP in simple steps

Install VIM and Dependencies
sudo apt-get install vim-runtime vim-common vim-gui-common vim-tiny curl exuberant-ctags

Clone the GIT repo to your HOME directory and go there
cd ~/
git clone https://github.com/bkozora/vim-php

cd vim-php

Create Symbolic Link to vim-ide so vim can find it
ln -s ~/vim-ide ~/.vim
ln -s ~/vim-ide/vimrc ~/.vimrc

This version utilizes Vundle to handle plugin dependencies. I finally got fed up with git submodules in multiple
environments, this method works better.

There's a number of features built in; too many to discuss here. Soon I'll list them but for now check out the 
mappings files for details on mapped shortcuts. You can also run :map from inside of vim.

Happy Coding!
Bobby Kozora

