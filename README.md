# dotfiles

Followed some steps at https://medium.com/@oldwestaction/beautifying-your-terminal-with-zsh-prezto-powerlevel9k-9e8de2023046

## Homebrew
https:/brew.sh/

## Prezto
https://github.com/sorin-ionescu/prezto

Change Prezto theme to `powerlevel10k`:

```
zstyle ':prezto:module:prompt' theme 'sorin'
```
to
```
zstyle ':prezto:module:prompt' theme 'powerlevel10k'
```

Then complete the cmdline wizard.

## iTerm2
```
brew cask install iterm2
```

## Tomorrow Night theme
https://github.com/chriskempson/tomorrow-theme

## iTerm2: configure
* change iTerm from Login shell to Command: /bin/zsh --login
* import Colors Presets from tomorrow-theme repo
* change starting dimensions

## Alfred app
* install Alfred
* Spotlight hotkey: turn off 
** System Preferences > Spotlight > Keyboard Shortcuts > Show Spotlight Search
* set Alfred hotkey

## Caffeine
http://lightheadsw.com/caffeine/

## VIM plugin: Commentary
https://github.com/tpope/vim-commentary
