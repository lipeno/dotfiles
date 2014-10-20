# Steps to setup new OS X Machine

## OS X configuration
- Move dock to left
- Desktop & Screen Saver -> Disable translucent menu bar
- Mission Control -> Hot Corners:
  - Upper-right: Put Display to Sleep
  - Lower-left: Desktop
  - Lower-right: Mission Control
- Universal Access
  - Flash the screen when an alert occurs
- Displays
  - Show displays in menu bar
- Set Keyboard
  - Disable "Automatically illuminate keyboard in low light"
  - Use all F1, F2, etc. keys as standard function keys
  - Key Repeat = Fast
  - Modifier Keys -> swap control/capslock

## Install
- Chrome
- Dropbox
- F.lux
- Induction
- Spectacle
- Flycut
- Right Zoom
- launchrocket (https://github.com/jimbojsb/launchrocket/releases)
- Skype
- VLC
- iTerm2
  - enable "load preferences from user-defined folder" -> "/Dropbox/Development/dotfiles
  - Preferences -> Colors -> Load Presets -> Solarized Dark
- Xcode
  - Open XCode and install the command line tools or run command "xcode-select --install"
- Magic Prefs
  - enable Middle click
- homebrew
  - /usr/bin/ruby -e $(curl -fsSL https://raw.github.com/mxcl/homebrew/master/Library/Contributions/install_homebrew.rb)
  - rub "brew doctor" to check if it was installed
- rvm + ruby on rails
  - https://get.rvm.io | bash -s stable --rails --autolibs=enable
- git
  - brew install git
- git auto complete
  - curl https://raw.github.com/git/git/master/contrib/completion/git-completion.bash -o ~/.git-completion.bash
  - echo "source ~/.git-completion.bash" >> ~/.bash_profile
- Sublime Text 3, Atom
  - then symlink it like "ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" ~/bin/subl"
- PostgreSQL
  - install http://postgresapp.com/
- Heroku Toolbelt


## Dotfiles

Based on http://barryclark.co/creating-bashstrap/ (https://github.com/barryclark/bashstrap)

**Features:**
- Open your current directory in Sublime Text (with just 2 characters)
- Jump directories rapidly, without having to set aliases—using Z (my favorite feature!)
- Tab bar displays your current directory
- Git branch status inline
- ☠ ahoy! An easily customizable symbol 
- Stripped out extraneous text 	
- Colored 'ls'
- Syntax highlighted 'cat'
