# neoVim
Upgrade your boring Vim editor to look like Visual studio over command line using my custom configurations !!

## Step-1: Install pre-requisite tools required for my neovim configurations
```
sudo apt-install neovim
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
curl -sL https://deb.nodesource.com/setup_18.x | sudo bash -
```

## Step-2: Download configuration file
```
wget https://github.com/prashantdivate/neoVim/blob/master/init.vim
```

## Step-3: Copy configuration file
```
cp init.vim ~/.config/nvim/.
```

## Step-4: Launch `nvim ~/.config/nvim/init.vim`, run `:PlugInstall`

### PN min Version requirements:
NVIM v0.4.3 <br />
node v18.17.1
