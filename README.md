# vim-config
My .vim .vimrc

### Requirements
Use brew vim instead of mac vim

### Necessary Brew installation
```
brew install ctags
brew install ack
brew install cmake
```

### Installing YouCompleteMe
```
# Install Neccessary Dependencies (Java JDK 8)
brew install cmake python nodejs npm 

cd ~/.vim/plugged/YouCompleteMe

# Clone submodules
git submodule update --init --recursive

python3 install.py --clangd-completer --java-completer --ts-completer
```

### Installing Vundle Plugin
```vim +PluginInstall +qall```


### References
[How to Turn Vim Into a Lightweight IDE](https://dane-bulat.medium.com/how-to-turn-vim-into-a-lightweight-ide-6185e0f47b79)

[Vim: Setting up a Build System and Code Completion for C and C++](https://dane-bulat.medium.com/vim-setting-up-a-build-system-and-code-completion-for-c-and-c-eb263c0a19a1)
