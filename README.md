# zsh_config

Download iterm2

`$ brew cask install iterm2`


Download ohmyzsh

`sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`


Make it pretty:

`git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k`

`brew tap homebrew/cask-fonts`

`brew cask install font-hack-nerd-font`


Download autocomplete:

`git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`


Uncomment lines 80 + 81 in `~/.oh-my-zsh/lib/key-bindings.zsh` to enable autocomplete search with up and down arrows


#### Manual settings:

open new tab from current dir

`iterm > preferences> profiles > general > Working Directory: reuse previous session's dir`


to make iterm key shortcuts like mac key shortcuts:

`iterm > preferences> profiles > keys > presets: natural text editing`

to add color profile

`iterm > preferences> profiles> colors> color presets> import`

add icons

`iterm > preferences> profiles> text > Font> Droid Sans Mono for Powerline (size 18)`

`iterm > preferences> profiles> text > Non-ASCII Font> Hack Nerd Font (size 18)`

`iterm > preferences> profiles> text > Non-ASCII Font> check use ligatures and anti-aliased boxes`


