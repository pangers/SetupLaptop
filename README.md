## Pangers' machine setup

1. Add `git-completion.bash` and `git-prompt.sh` to `~` directory
2. Add the following into `.bash_profile` to enable git features in terminal:

```
# Enable tab completion
source ~/git-completion.bash

# colors!
green="\[\033[0;32m\]"
blue="\[\033[0;34m\]"
purple="\[\033[0;35m\]"
reset="\[\033[0m\]"
cyan="\[\033[36m\]"

# Change command prompt
source ~/git-prompt.sh
export GIT_PS1_SHOWDIRTYSTATE=1

# '\u' adds the name of the current user to the prompt
# '\$(__git_ps1)' adds git-related stuff
# '\W' adds the name of the current directory
export PS1="$cyan\t $purple\u$green\$(__git_ps1)$blue \W $ $reset"

```

3. Add following to `.bash_profile` easily see hidden files:

```
alias showFiles='defaults write com.apple.finder AppleShowAllFiles YES; killall Finder /System/Library/CoreServices/Finder.app'
alias hideFiles='defaults write com.apple.finder AppleShowAllFiles NO; killall Finder /System/Library/CoreServices/Finder.app'
```

4. Install `rbenv`
5. Install `nvm`
6. Install a terminal theme you like eg. [Solarized](https://github.com/tomislav/osx-terminal.app-colors-solarized)
7. Instal `pyenv`


## Dev programs
- [Xcode](https://developer.apple.com/xcode/)
- [Android Studio](https://developer.android.com/studio)
- [Git](https://git-scm.com/downloads)
- [Sublime](https://www.sublimetext.com/)
- [MacDown](https://macdown.uranusjr.com/)
- [Gifski](https://gif.ski/)
- [GIPHY capture](https://giphy.com/apps/giphycapture)
- [scrcpy](https://github.com/Genymobile/scrcpy)
- [Fork](https://git-fork.com/)
- [Google Drive](https://www.google.com/drive/download/)
