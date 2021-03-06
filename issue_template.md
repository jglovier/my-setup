## Configure OS preferences, shortcuts, etc
- [ ] Update to the latest OSX patch
- [ ] Set new system password
- [ ] Turn on hard drive encryption
- [ ] Trackpad
  - [ ] Turn on 1 click touch
  - [ ] Enable three finger touch to drag (`System Prefs > Accessibility > Pointer Control > Mouse & Trackpad > Trackpad Options... > Enable Dragging > Three finger drag`)
- [ ] Spotlight: change to `alt A` for Spotlight search
- [ ] Turn off global font smoothing (`System Preferences > General > (uncheck) Use LCD font smoothing when available`)
- [ ] Global Shortcuts (`System Preferences > Keyboard > Shortcuts > App Shortcuts`): 
  - [ ] `cmd shift +` for Window > Zoom (just type `Zoom`)
- [ ] App Shortcuts (`System Preferences > Keyboard > Shortcuts > App Shortcuts`)
  - [ ] Sketch: `Show Sidebar` = `cmd 1`
  - [ ] Sketch: `Show Inspector` = `cmd 2`
- [ ] Dock
  - [ ] Check automatically show and hide
- [ ] Finder
  - [ ] Setup sidebar
  - [ ] Setup [default arrangement view](https://howchoo.com/g/mzuxyjqyzmy/how-to-set-the-view-options-for-all-finder-windows-in-os-x)
    - Arrange by: Name
    - Sort by: Name
    - Check Show item Info
    - Click `Use as Defaults`
  - [ ] Turn on [view hidden files](https://gist.github.com/jglovier/f87661ad2d10fa747ad6fcbbf7224305)
- [ ] Energy Saver: Turn off slightly dim display on battery power
- [ ] Security
  - [ ] Turn on FileVault disk encryption
  - [ ] Set to require password immediately
  - [ ] Turn on Firewall (?)
- [ ] Display (*if MBP 13")
  - [ ] Set display to Scaled (`System Preferences > Display > Resolution`) and set to `Looks like 1280 x 800`
- [ ] Customize touch bar
  - [ ] In control strip, replace Siri with Sleep (`System Preferences > Keyboard > Customize Control Strip...`)
- [ ] Configure where [screenshots should be stored](https://www.hellotech.com/guide/for/how-to-change-where-screenshots-are-saved-on-mac)

## Applications
- [ ] General
  - [ ] Go to App Store > Purchased and download all necessary
    - [ ] Slack (remote control no longer available in Slack, so App store version is fine)
    - [ ] ByWord
    - [ ] 1Password
    - [ ] TextExpander
    - [ ] DaisyDisk
    - [ ] Magnet
    - [ ] etc
- [ ] [Dropbox](https://www.dropbox.com/install)
- [ ] [Chrome](http://www.google.com/chrome/)
  - [ ] Set to confirm on `Cmd Q` for Quit
  - [ ] Log in and sync bookmarks and extensions
- [ ] [GitHub Desktop](https://desktop.github.com/)
- [ ] [Sketch](http://www.sketchapp.com/)
  - [ ] [SketchRunner](https://sketchrunner.com/)
- [ ] [Adobe Creative Cloud](http://www.adobe.com/creativecloud.html)
  - [ ] Photoshop
  - [ ] Illustrator
  - [ ] Acrobat
- [ ] [Bartender 4](https://www.macbartender.com/) for keeping my Menu bar tidy
- [ ] [Transmit](https://panic.com/transmit/) for FTP use
- [ ] [Cloak](https://www.getcloak.com/) for staying secure on the road
- [ ] [Traktor 2](http://www.native-instruments.com/en/products/traktor/dj-software/traktor-pro-2/) for making mixes
- [ ] [OpenEmu](http://openemu.org/) for old school SNES gaming
- [ ] [LICEcap](http://www.cockos.com/licecap/) for recording gifs
- [ ] [ImageOptim](https://imageoptim.com/) for optimizing ALL OF THE PNGS/JPGS
- [ ] [CleanMyMac](http://macpaw.com/cleanmymac) for keeping my machine cruft free
- [ ] [Kap](https://getkap.co/) for recording gifs (newer way)
- [ ] [Ableton Live](https://www.ableton.com/en/account/) for making sick beats
- [ ] [Spectacle](https://www.spectacleapp.com/) for window management
- [ ] [Sophos](https://home.sophos.com/download-mac-anti-virus) for security
- [ ] [Farrago](https://rogueamoeba.com/farrago/) for soundfx fun

## CLI
- [ ] Install command line tools: run `xcode-select --install` in iTerm
- [ ] Install [iTerm2](https://www.iterm2.com/)
  - [ ] Copy `.gitconfig` contents into global `~/.gitconfig`
  - [ ] Copy `.gitignore_global` to `~/`
- [ ] Install [Homebrew](https://brew.sh/)
- [ ] Install [oh my zsh](http://ohmyz.sh/)
  - [ ] Copy `.zshrc` to `~/`
  - [ ] Install [Powerline patched fonts](https://github.com/powerline/fonts/)
- [ ] Install iTerm theme
  - [ ] `iTerm2 > Preferences > Profiles > Other actions... > Import JSON Profiles... > [load dotfiles/jglovier-iterm-profile.json]`
- [ ] Install Ruby
  - [ ] Install `rbenv` via Homebrew: `brew install rbenv`.
  - [ ] Download a version of Ruby via rbenv (e.g., `rbenv install 2.7.1`). See <https://gorails.com/setup/osx/10.11-el-capitan>.
  - [ ] Make it the global version of Ruby: `rbenv global 2.7.1`.
- [ ] Install Node
  - [ ] [Install `nvm`](https://github.com/nvm-sh/nvm#installing-and-updating)
  - [ ] Install a version of Node via nvm (e.g., `nvm install node`) [See usage details](https://github.com/nvm-sh/nvm#usage)
  
## Visual Studio Code

- [ ] Install [VS Code](https://code.visualstudio.com/)
- [ ] Install extensions
  - [ ] [Apollo GraphQL](https://marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo)

## GitHub
- [ ] [Generate new SSH key](https://help.github.com/articles/generating-an-ssh-key/)
- [ ] [Generate an access token](https://help.github.com/articles/creating-an-access-token-for-command-line-use/) for Terminal to auth your GitHub account when 2FA is enabled.

## Backup
- [ ] Configure TimeMachine and perform initial backup
  - [ ] Turn off, and set Cal reminder to perform manually each week
