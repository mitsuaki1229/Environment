## Target

* MacBook Air (Retina, 13-inch, 2018)
    - Mac OS Mojave 10.14.3

## Local settings

### .bash_profile

```bash
$ curl https://gist.githubusercontent.com/mitsuaki1229/bdb587f8dc65a772afecd4dd72183b58/raw/.bash_profile > ~/.bash_profile
$ source ~/.bash_profile
```

### Git

```bash
$ curl https://gist.githubusercontent.com/mitsuaki1229/636c591cb540da82c1c1bd65320a6e7e/raw/.gitconfig > ~/.gitconfig
```

```bash
$ mkdir -p ~/.git_template/hooks/
$ curl https://gist.githubusercontent.com/mitsuaki1229/ad6c0998220ff3dcc7dcd45eacdcb98d/raw/pre-push > ~/.git_template/hooks/pre-push
```

## Tools install

### Homebrew

```bash
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

```bash
$ brew cask install dropbox
$ brew cask install inkdrop
$ brew cask install google-japanese-ime
$ brew cask install google-chrome
$ brew cask install alfred
$ brew cask install intellij-idea
$ brew cask install appcode
$ brew cask install the-unarchiver
$ brew cask install iterm2
$ brew cask install keepassxc
$ brew cask install visual-studio-code
$ brew cask install docker
$ brew cask install microsoft-office
$ brew cask install dash
$ brew cask install evernote
$ brew cask install bettertouchtool
$ brew cask install google-cloud-sdk
$ brew cask install slack
$ brew cask install caffeine
$ brew cask install android-platform-tools
$ brew install docker-compose
$ brew install rbenv
$ brew install git
$ brew install bash-completion
$ brew install carthage
$ brew install mas
$ brew install tig
```

### ruby

```bash
$ rbenv install 2.6.1
$ rbenv versions
$ rbenv global 2.6.1
$ rbenv rehash
$ ruby --version
ruby 2.6.1p33 (2019-01-30 revision 66950) [x86_64-darwin18]
```

#### gem

```bash
$ gem install xcode-install
```

#### Xcode

```bash
$ xcversion install 10.1
```

### App Store

```bash
$ mas list
595374522 VirusScannerPlus (3.14)
417375580 BetterSnapTool (1.9)
824171161 Affinity Designer (1.6.1)
824183456 Affinity Photo (1.6.7)
508368068 Get Plain Text (2.0)
```

## Other Setting

* iTerm2 -> Preference -> Profiles -> Terminal -> Set locale variables automatically
    - [ ] untick
* Alfred Preferences -> Clipboard -> Keep Plain Text
    - [ ] untick
* [ ] Mac Language settings English.
* [ ] US Key Swap Control <-> Caps Lock
* System Preferences -> Keyboard
    - [ ] Key Repeat Fast
    - [ ] Delay Until RepeatShort
* [ ] Remove keep app in Dock.
* [ ] Change PC name.
    ```bash
    $ scutil --set ComputerName mitsuaki1229-mba
    $ sudo scutil --set LocalHostName mitsuaki1229-mba
    $ sudo shutdown -r now
    ```
* [ ] Replace input sources with google-japanese-ime.
* [ ] Setting ssh config.