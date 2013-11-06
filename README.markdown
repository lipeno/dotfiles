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
