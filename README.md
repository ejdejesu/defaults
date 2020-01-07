# defaults
files and stuff for my linux setup

## Programs/Plugins

- [zsh](https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH)  
- [ohmyzsh](https://github.com/robbyrussell/oh-my-zsh)
- [docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
- [albert](https://albertlauncher.github.io/docs/installing/)
- [spotify](https://www.spotify.com/us/download/linux/)
- [terminator](https://gnometerminator.blogspot.com/p/introduction.html)
- [Arc Menu](https://www.fossmint.com/arc-menu-an-alternative-app-launcher-for-gnome-shell/)
- [Numix Icons](https://github.com/numixproject/numix-icon-theme)
- [vscode](https://code.visualstudio.com/docs/setup/linux)
- redshift
- [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono?selection.family=Roboto+Mono)

## Necessary commands
```
sudo ln -s $(pwd)/.vimrc $HOME/.vimrc
sudo ln -s $(pwd)/.zshrc $HOME/.zshrc
sudo ln -s $(pwd)/.zsh_aliases $HOME/.zsh_aliases
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
