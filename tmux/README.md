##Tmux

###[Tmux](http://tmux.github.io) uses the tmux.conf file for configurations.

#### Tmux-config content:
* Remap prefix from 'C-b' to 'C-a'
* Split panes using | and -
* Reload config file with bind 'R'
* Switch panes using Alt-arrow without prefix
* Resize panes using k(down), i(up), j(left), l(right)
* Design changes on Panes/Status Bar/Messaging/Window Mode/Window Status/Info
* Loud or quiet?
* Modes/Panes/Statusbar/Messages colors
* and some more

##### List of plugins used:
*  tmp
*  tmux-sensible
*  tmux-resurrect
*  tmux-continuum
*  tmux-powerline

#### Install Tmux
```bash
./make.sh
```

#### Note
Remember, the config file is store on `~/.tmux.conf`, and the config file for the tmux status bar is on `~/tmux-powerline/themes/mytheme.sh`
