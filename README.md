# Quick Guide on How to Setup your Neovim

### Install Neovim 0.10+

```
> sudo add-apt-repository ppa:neovim-ppa/unstable
> sudo apt-get update
> sudo apt-get install neovim
```

### Add vim-plug

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

### Install Plugins

```
> nvim ./
:PlugInstall
```

### Verify all your plugins are installed 

