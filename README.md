# General

This is my personal tmux configuration, meant to interoperate with my nvim config which can be found at [github.com/buxogabriel/nvim-config](github.com/buxogabriel/nvim-config)

# Installation

Clone this tmux config into `XDG_CONFIG_HOME/tmux` or `$HOME/.tmux.conf`

# Post Installation

If you are alredy in tmux you will have to reload the configuration by running the tmux source command on the `tmux.conf` file

Enter tmux and install packages with `<Prefix> I` and update them using `<Prefix U>`

# Features

- prefix is updated from Ctrl-b to Ctrl-Space
- prefix -> Shift + Alt + H moves to previous window and Shift + Alt + L moves to next window
- Splitting pane with prefix-" keeps the pane in the same directory and resizes it so it is only 15 lines tall
- Makes windows and panes 1 indexed for easier navagability
- Adds plugins including tmux-navigator that allow for movement from nvim panes to tmux panes
