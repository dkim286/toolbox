# `util/`

Contains all the utility scripts.

## Dependencies

* feh
* tree

## Scripts

### `fakeinstall`

Drops a symlink to FILENAME in '/usr/local/bin'

### `gui-auth`

Runs polkit-gnome-authentication-agent-1 for 30s (default) or as defined by argument

### `uh`

The thing that helps me remember. This script displays a list of available toolbox scripts.

Requires `$TOOLBOX` to be defined.
Sourcing `uh-completion.bash` is *very* helpful, but optional.

Example usage:
```
$ uh
office (1)
util (4)

$ uh util
util/fakeinstall
    Drops a symlink to FILENAME in /usr/local/bin
util/gui-auth
    Runs polkit-gnome-authentication-agent-1 for 30s (default) or as defined by argument
util/uh
    Shows a list of available toolbox scripts
util/wallpaper
    Automatically cycles through wallpapers in $HOME/Pictures/wp
    
$ uh -t
toolbox
├── office
│   └── makepdf
└── util
    ├── fakeinstall
    ├── gui-auth
    ├── uh
    └── wallpaper
```


### `wallpaper`

Automatically cycles through wallpapers in $HOME/Pictures/wp by calling `sleep`. It's better used as an exec entry in `.xinitrc` or something.


