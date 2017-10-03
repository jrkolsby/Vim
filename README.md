# 1. Install Vim Config

If there is a previous Vim install:
```
mv ~/.vim ~/.vim_old && mv ~/.vimrc ~/.vimrc_old
```
Install
```
git clone https://github.com/jrkolsby/Vim.git ~/.vim && echo "runtime vimrc" > ~/.vimrc
```

# 2. Install Plugins*

```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
vim
:PluginInstall
```

## Plugins
1. Vundle
2. NerdTree
3. Emmet 
4. Handlebars Syntax

# 3. Intall Bash config
```
mv ~/.vim/.bashrc ~/.bashrc
# IF on a MacOS machine:
mv .bashrc .bash_profile
```

# 4. Color Pallette
- [ ] Make Color Pallette
- [ ] Figure out how to spell palette

