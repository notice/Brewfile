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
install git
install vim
install wget
install curl
install mysql
install postgresql
install python
install ansible
# $ curl -L git.io/nodebrew | perl - setup
# install nodebrew
install ffmpeg --with-theora --with-libogg --with-libvorbis
install tree

install fish
install go
install peco
install z

install tmux
install reattach-to-user-namespace

# dnsmasq
install dnsmasq

#aws
install awscli

# php
# xcode-select --install
install php56 --with-postgresql --with-pdo-pgsql --with-pdo-mysql --enable-opcache
install php56-mcrypt php56-xdebug php56-redis composer
install php56-memcached --with-sasl
install phpunit phpunit-skeleton-generator

# ruby
install readline
install openssl
install rbenv
install ruby-build

# Packages for brew-cask
# install brew-cask

# .dmg from brew-cask
cask install dropbox
cask install google-chrome
cask install virtualbox
cask install vagrant
cask install vagrant-manager
cask install github
cask install google-japanese-ime
cask install atom
cask install skitch
cask install alfred
cask install iterm2
cask install android-studio

# Remove outdated versions
cleanup
