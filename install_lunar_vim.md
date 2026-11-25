# Install Lunar Vim
The following steps were tested on macOS 15.6.1.

Firstly, install all the following packages with brew:
```
brew install git
brew install node
brew install python
brew install neovim
brew install lua
```

(Obviously, check to see if they are installed first e.g. by calling `git`.)

Then install Cargo:
```
curl https://sh.rustup.rs -sSf | sh
```

Finally, install Lunar Vim:
```
bash <(curl -s https://raw.githubusercontent.com/lunarvim/lunarvim/master/utils/installer/install.sh)
```

The installer will ask you if you want to install various programming language dependencies. Press `y` for the ones you want, presumably NodeJS and Python.

You can now use Lunar Vim with `lvim`.

# Install iTerm
Lunar Vim will likely look like crap when used with a macOS's default Terminal. Therefore, install iTerm:
```
brew install --cask iterm2
```

Modifying your Terminal profile (e.g. font) will then modify the appearance of Lunar Vim.
