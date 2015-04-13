# Make sure using latest Homebrew
update

# Update already-installed formula
upgrade

# Add Repository
tap homebrew/versions || true
tap caskroom/homebrew-cask || true
tap homebrew/binary || true
tap josegonzalez/php || true

# Packages for development
install zsh --disable-etcdir
install zsh-completions
install fish
install git
install vim
install wget
install curl
install mysql
install postgresql
install python
install ansible
install nodebrew
install ffmpeg --with-theora --with-libogg --with-libvorbis

install tmux
install go
install peco

# php
install php56 --with-pgsql --with-pdo-pgsql --with-pdo-mysql --enable-opcache
install php56-mcrypt php56-xdebug php56-redis composer
install php56-memcached --with-sasl
install phpunit phpunit-skeleton-generator

# ruby
install readline
install openssl
install rbenv
install ruby-build

# Packages for brew-cask
install brew-cask

# .dmg from brew-cask
cask install dropbox
cask install google-chrome
cask install virtualbox
cask install vagrant
cask install vagrant-manager
cask install kobito
cask install github
cask install google-japanese-ime
cask install atom
cask install dash
cask install skitch
cask install alfred
cask install iterm2

# Remove outdated versions
cleanup
