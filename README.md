My terminal configs

![Iterm2 + zsh + tmux + powerline](/../screenshots/screenshots/screenshots/tmux-zsh.png?raw=true "Iterm2 + zsh + tmux + powerline")

Installation:
---------
iTerm2:
https://www.iterm2.com/

homebrew:
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

python:
brew install python

tmux:
brew install tmux

reattach-to-user-namespace:
brew install reattach-to-user-namespace

zsh
curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh

psutil:
pip install psutil

powerline:
pip install git+git://github.com/powerline/powerline

powerline fonts:
git clone git@github.com:powerline/fonts.git powerline-fonts
cd powerline-fonts
./install.sh

Copy configs from this repo into home directory
Change your Iterm2 font to one of the powerline-fonts
