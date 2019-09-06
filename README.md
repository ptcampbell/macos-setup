### 🐣 macOS Environment

_Ditching the shell script in favor of a simple recipe due to broken, deprecated taps etc._

#### 🍺 Homebrew

Paste into Terminal…

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

#### 🐢 Shell things

```
brew cask install hyper

// install zsh
brew install zsh

// install oh-my-zsh
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

// shell plugins
brew install zsh-autosuggestions
brew install autojump
```

_Restart is required for shell default to take effect_

#### 🖥 Apps

```
brew cask install google-chrome
brew cask install firefox
brew cask install dropbox
brew cask install visual-studio-code
brew cask install tower
brew cask install sketch
brew cask install forklift
brew cask install spotify
brew cask install cleanmymac
brew cask install docker
brew cask install sequelpro
brew cask install dash
brew cask install istat-menus
brew cask install pocket-casts
brew cask install private-internet-access
brew cask install focus
brew cask install hazeover
brew cask install wake
brew cask install airfoil
brew cask install kaleidoscope
brew cask install mosaic
```


*Apps requiring manual installation*
```
f-Bar
adobe creative cloud
```

#### 🍎 App Store Apps

Can be installed via MAS…

```
brew tap mas-cli/tap
brew tap-pin mas-cli/tap
brew install mas
```

…or via the Mac App Store (I think it’s quicker via App Store > Account > Purchased)

```
1password
xcode
pastebot
ia-writer
slack
things 3
tweetbot
gifox
daisydisk
```

#### 🖥 Development

```
brew install wget
brew install yarn
brew install node
brew install yarn
brew install nginx
brew install php

// download composer
curl -sS https://getcomposer.org/installer | php

// move composer
sudo mv composer.phar /usr/local/bin/composer

composer global require laravel/installer
```
