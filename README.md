🥚 My 2018 macOS environment

_Ditching the shell script in favor of a simple recipe due to stale or broken brews etc._

### 🍺 Homebrew

Paste into Terminal…

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

### 🐢 Shell things

```
brew cask install hyper

Install zsh:
brew install zsh

Install oh-my-zsh:
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

Shell plugins: 
brew install zsh-autosuggestions
brew install autojump
```

_Restart is required for shell default to take effect_

### 🖥 Apps

```
brew cask install google-chrome
brew cask install firefox
brew cask install brave-browser
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
brew cask install wake
```


#### Apps requiring manual installation
```
Airfoil
Kaleidoscope
Mosaic
F-Bar
```

### 🍎 App Store Apps

Can be installed via MAS…

```
brew tap mas-cli/tap
brew tap-pin mas-cli/tap
brew install mas
```

…or via the Mac App Store (I think it’s quicker via App Store > Account > Purchased)

- Xcode
- 1Password
- Pastebot
- Spark
- Bear
- Slack
- Things 3
- Tweetbot
- Gifox
- Daisydisk

### 🖥 Development

…
