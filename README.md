# zsh
My repo for keeping Z shell stuf

## Instalation
```
cd ~
git clone https://github.com/RamiroOliveira/zsh.git ~/.zsh
ln -s ~/.zsh/zshrc ~/.zshrc
source ~/.zshrc
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
cd ~/.oh-my-zsh/custom/plugins
git clone https://github.com/zsh-users/zsh-autosuggestions.git
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
ln -s ~/.zsh/p10k.zsh ~/.p10k.zsh
source ~/.zshrc
```

