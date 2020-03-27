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
  - [ ] Sketch: `Show Layers List` = `cmd 1`
  - [ ] Sketch: `Show Inspector` = `cmd 2`
- [ ] Dock
  - [ ] Move to left side
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
- [ ] [Customize touch bar](https://support.apple.com/en-us/HT207055)
  - [ ] In control strip, replace Siri with Sleep

## Applications
- [ ] General
  - [ ] Go to App Store > Purchased and download all necessary
    - [ ] Slack (remote control no longer available in Slack, so App store version is fine)
    - [ ] ByWord
    - [ ] Xcode
      - [ ] Also install [Command Line Tools](https://gist.github.com/jglovier/842c61d5a4347cdc18f812e2ef7c2928)
    - ~~Sketch~~ (not from App store anymore, download from site)
    - [ ] 1Password
    - [ ] TextExpander
    - [ ] DaisyDisk
    - [ ] etc
- [ ] [Dropbox](https://www.dropbox.com/install)
- [ ] [Chrome](http://www.google.com/chrome/)
  - [ ] Set to confirm on `Cmd Q` for Quit
  - [ ] Log in and sync bookmarks and extensions
- [ ] [Atom](http://atom.io)
- [ ] [GitHub Desktop](https://desktop.github.com/)
- [ ] [Sketch](http://www.sketchapp.com/) *(from App store)*
  - [ ] [SketchRunner](https://sketchrunner.com/)
- [ ] [Figma desktop](https://www.figma.com/downloads/)
- [ ] [Fantastical 2](https://flexibits.com/fantastical)
  - [ ] Check Appearance > Use color icon
- [ ] [Adobe Creative Cloud](http://www.adobe.com/creativecloud.html)
  - [ ] Photoshop
  - [ ] Illustrator
  - [ ] Acrobat
- [ ] [Bartender 2](https://www.macbartender.com/) for keeping my Menu bar tidy
- [ ] [Transmit](https://panic.com/transmit/) for FTP use
- [ ] Apple Mail (or [Nylas](https://nylas.com/))
  - [ ] Configure email accounts
- [ ] [Cloak](https://www.getcloak.com/) for staying secure
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
- [ ] Install command line tools: run `xcode-select —install` in iTerm
- [ ] Install [iTerm2](https://www.iterm2.com/)
  - [ ] Load `.bash_profile`
  - [ ] Load `.gitconfig` contents into global `~/.gitconfig`
  - [ ] Load `.gitignore_global`
- [ ] Install [Homebrew](https://brew.sh/)
- [ ] Install [oh my zsh](http://ohmyz.sh/)
  - [ ] Load `.zshrc`
  - [ ] Install [Powerline patched fonts](https://github.com/powerline/fonts/)
- [ ] Set iTerm preferences
  - [ ] Install [Galaxy theme](https://github.com/jglovier/galaxy-theme-iterm)
  - [ ] Set text to:
    - Regular font: `14pt Roboto Mono for Powerline`
    - Non-ASCII font: `12pt Meslo LG L DZ Regular for Powerline`
- [ ] Install Ruby
  - [ ] Install rbenv via Homebrew: `brew install rbenv`.
  - [ ] Download a version of Ruby via rbenv (e.g., `rbenv install 2.5.1`). See <https://gorails.com/setup/osx/10.11-el-capitan>.
  - [ ] Make it the global version of Ruby: `rbenv global 2.5.1`.
- [ ] Install misc dependencies
  - [ ] Install Node via Homebrew: `brew install node`
  - [ ] Install Sass, Jekyll, and Rouge: `gem install sass jekyll rouge`.
  
## Visual Studio Code

- [ ] Install [VS Code](https://code.visualstudio.com/)
- [ ] Install extensions
  - [ ] [Apollo GraphQL](https://marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo)

## Atom
- [ ] Enable `atom` Terminal commands: from Atom.app, open the Atom menu and select *Install Shell Commands*
- [ ] Disable the `wrap-guide` package
- [ ] Install [favorite packages](https://atom.io/users/jglovier/stars):
  - [ ] [Wrap in tag](https://atom.io/packages/atom-wrap-in-tag)
  - [ ] [Selector to tag](https://atom.io/packages/selector-to-tag)
  - [ ] [Linter](https://atom.io/packages/linter) and [linter-stylelint](https://atom.io/packages/linter-stylelint)
  - [ ] [Autoclose HTML](https://atom.io/packages/autoclose-html)
  - [ ] [Compare files](https://atom.io/packages/compare-files)
  - [ ] [Less than slash](https://atom.io/packages/less-than-slash)
  - [ ] [Merge conflicts](https://atom.io/packages/merge-conflicts)
  - [ ] [Git-time-machine](https://atom.io/packages/git-time-machine)
  - [ ] [Atom beautify](https://atom.io/packages/atom-beautify)
  - [ ] [Markdown PDF](https://atom.io/packages/markdown-pdf)
  - [ ] [Markdown Writer](https://atom.io/packages/markdown-writer)
  - [ ] [Toolbar for Markdown Writer](https://atom.io/packages/tool-bar-markdown-writer)

## GitHub
- [ ] [Generate new SSH key](https://help.github.com/articles/generating-an-ssh-key/)
- [ ] [Generate an access token](https://help.github.com/articles/creating-an-access-token-for-command-line-use/) for Terminal to auth your GitHub account when 2FA is enabled.

## Backup
- [ ] Configure TimeMachine and perform initial backup
  - [ ] Turn off, and set Cal reminder to perform manually each week

## Misc
- [ ] Install Fonts from backup fronts dir
- [ ] Download music from Apple Music
