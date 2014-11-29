# Brew file for Yosemite
# Requirements:
#  - Install Xcode 6.1 or later
#  - Install Xcode Developer Tool
#    - https://developer.apple.com/downloads/index.action
#    - Command Line Tools (OS X 10.10) for Xcode - Xcode 6.1

# update Homebrew
update

# Add Repository
tap caskroom/homebrew-cask
tap sanemat/font

# install brew packages
install ack
install ant
#install apple-gcc42 # unavailable on yosemite
install archey
install autoconf
install bazaar
install bdw-gc
install boost
install brew-cask
#install cairo       # unavailable on yosemite
install cloog
install cmake
install colordiff
install coreutils
install curl
install erlang
install fontconfig
#install fontforge   # unavailable on yosemite
install freetype
install gcc
#install gdb         # unavailable on yosemite
install gdbm
install gettext
install ghc
install git
install git-flow
install glib
install gmp
install go
install gobject-introspection
install graphviz
#install harfbuzz    # unavailable on yosemite
#install haskell-platform
install icu4c
install isl
install jpeg
install jq
install libevent
install libffi
install libmpc
install libpng
install libtiff
install libtool
install libxml2
install logrotate
install maven
install mercurial
install mpfr
install mysql
install nginx
install node
install openssl
install ossp-uuid
#install pango      # unavailable on yosemite
install pcre
install phantomjs
install pixman
install pkg-config
install popt
install postgresql
install python
install rbenv
install readline
#install --vim-powerline ricty  # unavailable on yosemite
install ruby-build
#install screen    # unavailable on yosemite
install shunit2
install sqlite
install terminal-notifier
install tmux
install tree
install unixodbc
install vim
install w3m
install wget
install wxmac
install xz
#install xquartz   # unavailable on yosemite
install zsh

## brew cask applications
install brew-cask

# Browser
cask install google-chrome
cask install firefox
cask install opera

# Editor
cask install coteditor
cask install macvim
cask install mou
cask install zeroxed
cask install diffmerge

# Communication
cask install skype
cask install slack

# Network access
cask install filezilla
cask install cyberduck
cask install dropbox

# Terminal
cask install iterm2

# Virtual Machine
cask install virtualbox
cask install vmware-fusion

# Mobile
cask install iexplorer
cask install android-file-transfer
cask install android-studio

# Reader
cask install kobo

# Multimedia
cask install silverlight
cask install spotify

# Status bar
cask install clipmenu

# Dev tools
cask install sequel-pro

# Utility
cask install simplecap
cask install bettertouchtool
cask install cd-to
cask install omnidisksweeper


## Post process for font update(optional)
# 1. copy font
#   cp -f /usr/local/Cellar/ricty/*/share/fonts/Ricty*.ttf ~/Library/Fonts/
# 2. clear font cache
#   fc-cache -vf
# 3. restart shell
#   exec $SHELL -l

