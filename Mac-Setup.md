# Development Machine Setup

## Xcode
Install XCode from the Mac App Store

## Install Rosetta2 (M1 Macs Only)
```
softwareupdate --install-rosetta
```

## Install Homebrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew tap homebrew/cask
```

## Install Git
```
brew install git
```
## Install Node
```
brew install nvm
mkdir ~/.nvm
echo 'export NVM_DIR="$HOME/.nvm"' >> /Users/pjc/.zprofile
echo '[ -s "/opt/homebrew/opt/nvm/nvm.sh" ] && \. "/opt/homebrew/opt/nvm/nvm.sh"' >> ~/.zprofile
echo '[ -s "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" ] && \. "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm"' >> ~/.zprofile

source .zprofile

nvm install 17
nvm alias default node


```

## Install Google Chrome
```
brew install google-chrome
```

## Install Java Runtime
```
brew install jenv
echo 'export PATH="$HOME/.jenv/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(jenv init -)"' >> ~/.zshrc

brew install openjdk@17
brew install openjdk@11
brew install openjdk@8 # Non M1
Manual Install from: 
https://www.azul.com/downloads/?version=java-8-lts&os=macos&architecture=arm-64-bit&package=jdk#download-openjdk # M1

```


## Install AWS CLI
```
brew install awscli
```

## Install Docker
```
Install Manually from Docker
```

## Install Atom
```
brew install atom
```

## Install JetBrains Applications
```
brew install jetbrains-toolbox
```


## Install fluro 
Automatically switches function key behavior on a per App basis Setup FN keys to be default for IDEs
```
brew install fluor
```
