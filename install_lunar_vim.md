# Install LunarVim
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

Finally, install LunarVim:
```
bash <(curl -s https://raw.githubusercontent.com/lunarvim/lunarvim/master/utils/installer/install.sh)
```

The installer will ask you if you want to install various programming language dependencies. Press `y` for the ones you want, presumably Node.js and Python.

You can now use LunarVim with `lvim`.

# Install iTerm
LunarVim will likely look like crap when used with macOS's default Terminal. Therefore, install iTerm:
```
brew install --cask iterm2
```

Modifying your terminal profile (e.g. font) will then modify the appearance of LunarVim.

# Add font
SF Mono is a good font that ships with macOS's Terminal. To install it on the system so that iTerm can use it:
1) In Finder, navigate to Applications -> Utilities
2) Right click on Terminal and select Show Package Contents
3) Navigate to Contents -> Resources -> Fonts
4) Double click on the font you want and select Install
5) You will now be able to use the font in iTerm
