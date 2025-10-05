# mac-setup

## Homebrew

Absolutely phenomenal package manager
To install, run this in the terminal
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Now with Homebrew installed, we can install all the other apps I use in one easy step:
create a file called apps.txt and paste in these app names

```
discord
ffmpeg
hiddenbar
iterm2
itsycal
keka
localsend
neovim
raycast
rectangle
spotify
stats
visual-studio-code
vlc
```

And we can install all of them with this shell command
```sh
xargs brew install < apps.txt
```
## Raycast

Now that we have Raycast installed, add the homebrew extension to search and add homebrew packages as needed
Settings -> Extensions -> + -> add from store -> search homebrew and add

## Terminal

iterm2 is great
Settings:
minimal theme

Then install oh my zsh and lazyvim, just look them up and follow those instructions
