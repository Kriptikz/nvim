# Personal Neovim Config

## Installation

- On ubuntu the default installation of neovim through apt-get is outdated. 

Run the following commands to install a more up to date version:
```shell
sudo add-apt-repository ppa:neovim-ppa/unstable
sudo apt-get update
sudo apt-get install neovim
```

May need to also add prereq python modules:
```shell
sudo apt-get install python-dev python-pip python3-dev python3-pip
```

- Create and navigate to `~/.config` and clone this repo. This should create
a `~/.config/nvim` directory with all of the neovim settings. On startup of 
neovim it will install the plugins. 

- You may also need a compiler installed. Here is a command to install some
of the general dev tools:
```shell
sudo apt-get install libtool autoconf automake cmake libncurses5-dev g++
```



