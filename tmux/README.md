# tmux macOS

## Youtube Video
![macOS Developer Tools.](https://i4.ytimg.com/vi/SwwmPPT9JXI/mqdefault.jpg "tmux macOS | terminal in terminal")

https://youtu.be/SwwmPPT9JXI

:: To install all you will need [Homebrew](https://brew.sh/)

## Install

Go to link:
https://github.com/tmux/tmux/wiki

```
brew install tmux
```

# Plugins TPM
https://github.com/tmux-plugins/tpm

Put this at the bottom of ~/.tmux.conf
```
# List of plugins
set -g @plugin 'tmux-plugins/tpm'
set -g @plugin 'tmux-plugins/tmux-sensible'

# Other examples:
# set -g @plugin 'github_username/plugin_name'
# set -g @plugin 'github_username/plugin_name#branch'
# set -g @plugin 'git@github.com:user/plugin'
# set -g @plugin 'git@bitbucket.com:user/plugin'

# Initialize TMUX plugin manager (keep this line at the very bottom of tmux.conf)
run '~/.tmux/plugins/tpm/tpm'
```

```
# type this in terminal if tmux is already running
tmux source ~/.tmux.conf
```


# Catppuccin [Mocha] Theme
https://github.com/catppuccin/tmux

```
mkdir -p ~/.config/tmux/plugins/catppuccin
git clone -b v2.1.2 https://github.com/catppuccin/tmux.git ~/.config/tmux/plugins/catppuccin/tmux
```
Add the following line to your tmux.conf file: 
```
run ~/.config/tmux/plugins/catppuccin/tmux/catppuccin.tmux.
```


### Terminal tools

1. [Kitty](https://sw.kovidgoyal.net/kitty/)
2. [Warp](https://www.warp.dev/)
3. [Starship](https://starship.rs/)


:::::::::::::::::::::::::::
**KODY•AZ**
:::::::::::::::::::::::::::

https://www.kody.az/



