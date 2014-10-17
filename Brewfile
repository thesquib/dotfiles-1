# Install command-line tools using Homebrew
# Usage: `brew bundle Brewfile`

# Make sure we’re using the latest Homebrew
brew update

# Upgrade any already-installed formulae
brew upgrade

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
brew install coreutils
#sudo ln -s /usr/local/bin/gsha256sum /usr/local/bin/sha256sum

# Install some other useful utilities like `sponge`
brew install moreutils
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, `g`-prefixed
brew install findutils
# Install GNU `sed`, overwriting the built-in `sed`
brew install gnu-sed --default-names
# Install Bash 4
# Note: don’t forget to add `/usr/local/bin/bash` to `/etc/shells` before running `chsh`.
brew install bash
brew install bash-completion

# Install wget with IRI support
brew install wget --enable-iri

# Install RingoJS and Narwhal
# Note that the order in which these are installed is important; see http://git.io/brew-narwhal-ringo.
#brew install ringojs
#brew install narwhal

# Install more recent versions of some OS X tools
brew install vim --override-system-vi
brew install homebrew/dupes/grep
brew install homebrew/dupes/screen
#install homebrew/php/php55 --with-gmp

# Install some CTF tools; see https://github.com/ctfs/write-ups
#install bfg
#install binutils
#install binwalk
#install cifer
#install dex2jar
#install dns2tcp
#install fcrackzip
#install foremost
#install hashpump
#install hydra
#install john
#install knock
#install nmap
#install pngcheck
#install sqlmap
#install tcpflow
#install tcpreplay
#install tcptrace
#install ucspi-tcp # `tcpserver` et al.
#install xpdf
#install xz

# Install other useful binaries
#install ack
#install exiv2
brew install git
brew install imagemagick --with-eebp
brew install lynx
brew install node # This installs `npm` too using the recommended installation method
brew install p7zip
brew install pigz
brew install pv
brew install rename
brew install rhino
brew install tree
brew install webkit2png
brew install zopfli

brew install homebrew/versions/lua52

# Remove outdated versions from the cellar
brew cleanup
