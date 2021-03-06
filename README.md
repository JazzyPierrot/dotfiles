How to install
--------------


```bash
# clone this repo into ~/dotfiles
cd ~
git clone https://github.com/JazzyPierrot/dotfiles.git
sudo apt install stow
```

And then stow the config files you are interested in from inside the dotfiles 
repository:

```bash
cd ./dotfiles
stow nvim # Vim and nvim
stow bash # Bash and readline
stow tmux 
```

Vim configuration
=================

- Install Vundle, and do ":PluginInstall" inside nvim. 

Tmuxinator
==========

Tmuxinator is used to quickly open R and python sessions, with an alias in 
.bash_aliases, the commands are:
```bash
tx start R
tx start py
```

Bash configuration
==================

For the coloscheme, see 
https://github.com/aaron-williamson/base16-gnome-terminal for instructions
