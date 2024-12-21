# Quick Guide on How to Setup your Neovim

### Install dependencies

```
sudo apt-get install python3.x-venv
```

### Install Neovim 0.10+

```
> sudo add-apt-repository ppa:neovim-ppa/unstable
> sudo apt-get update
> sudo apt-get install neovim
```

### Add vim-plug

```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

### Install Plugins

```
> nvim ./
:PlugInstall
```

Note: You may need to run "R" because some plugins fail to install in the first try

### Install language servers

```
:LSPInstall 

```
