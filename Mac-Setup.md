# Development Machine Setup

## Xcode
Install XCode from the Mac App Store

## Install Homebrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew tap caskroom/cask
```

## Install iTerm2
```
brew cask install iterm2
```

## Install ZSH
```
brew install zsh zsh-completions
curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh
chsh -s /usr/local/bin/zsh
```

## Install Git
```
brew install git
```
## Install Node
```
brew install node
```

## Install Google Chrome
```
brew cask install google-chrome
```

## Install Java Runtime
```
brew tap caskroom/versions
brew cask install java8
```

To install a different version other then Java 8 you can view a list of version by running
```
brew tap caskroom/versions
brew search java

```

## Install Docker
```
brew cask install docker
open /Applications/Docker.app
```

## Install JetBrains Applications
```
brew cask install jetbrains-toolbox
```


## Install fluro 
Automatically switches function key behavior on a per App basis Setup FN keys to be default for IDEs
```
brew cask install fluor
```
