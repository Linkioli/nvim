## Requirements

- nodejs
```
# debian
sudo apt install nodejs npm
# arch
sudo pacman -S nodejs npm
```
- vim-plug
```
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

- language server dependencies
```
# bash language server
npm i -g bash-language-server
```

## Editor Setup
- Install plugins with vim-plug
```
:PlugInstall
```
- COC extensions (I hate the name of this plugin)
```
:CocInstall coc-sh coc-godot
```
