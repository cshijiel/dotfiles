# Setup up a new Mac

Inspired by [KrauseFx/new-mac](https://github.com/KrauseFx/new-mac).

## Setup Shell

- [ ] Install [Homebrew](https://brew.sh)
- [ ] Install [Brewfile](https://github.com/crispgm/dotfiles/blob/master/macOS/Brewfile)
- [ ] Choose a theme of Terminal.app from [osx-terminal-themes](https://github.com/lysyi3m/osx-terminal-themes)
- [ ] Login locally on GitHub
- [ ] Setup `.dotfiles`

## Install Fonts

- [ ] `brew tap caskroom/fonts && brew cask install font-source-code-pro font-fira-code`

## Ruby

To avoid ban from GFW:

- [ ] Setup Gem sources: `gem sources --add https://gems.ruby-china.org/ --remove https://rubygems.org/`
- [ ] Setup bundler's mirror: `bundle config mirror.https://rubygems.org https://gems.ruby-china.org`

In non China mainland area, it should be ignored.

## Shadowsocks

- [ ] Install [ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG)
- [ ] Import custom [user-rules](https://github.com/crispgm/dotfiles/tree/master/Shadowsocks)

## Sublime Text

- [ ] Migrate [.sublime-settings](https://github.com/crispgm/dotfiles/tree/master/macOS/Apps/Sublime)
- [ ] Create `subl` in Terminal: `sudo ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /Users/baidu/Applications/subl`
- [ ] Install [PackageControl](https://packagecontrol.io/)
- [ ] Install `Monokai-Spacegrey` with `PackageControl`
- [ ] Install [Tomorrow theme](https://github.com/chriskempson/tomorrow-theme.git)
- [ ] Install `syntax-highlighting-for-sass`, `vue-syntax-highlight` and `babel-sublime` with `PackageControl`

## Finder

- [ ] Show Path Bar
- [ ] Remove labels and clean up Sidebar

## Dock

- [ ] Add blank seperator: `defaults write com.apple.dock persistent-apps -array-add '{tile-data={}; tile-type="spacer-tile";}`