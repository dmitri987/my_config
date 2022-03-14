
### GNOME Keybindings API
`backup_gnome_keybindings` read current GNOME keybindings, save them to $GNOME_DIR/gnome_keybindings.ini and update README.md.
`set_gnome_keybindings < {keybindings}` restore GNOME keybindings from a backup file. Used in `setup` script.


### GNOME Keybindings
#### [org/gnome/desktop/wm/keybindings]
|<Alt>r|begin-resize|
|<Alt>q|close|
|<Super>Escape|cycle-windows|
|<Shift><Super>Escape|cycle-windows-backward|
|<Alt>k|maximize|
|<Shift><Alt>j|move-to-monitor-down|
|<Shift><Alt>h|move-to-monitor-left|
|<Shift><Alt>l|move-to-monitor-right|
|<Shift><Alt>k|move-to-monitor-up|
|<Shift><Super>h|move-to-workspace-1|
|<Shift><Super>j|move-to-workspace-down|
|<Shift><Super>l|move-to-workspace-last|
|<Shift><Super>k|move-to-workspace-up|
|<Super>Tab|switch-applications|
|<Shift><Super>Tab|switch-applications-backward|
|<Super>grave|switch-group|
|<Shift><Super>grave|switch-group-backward|
|<Super>h|switch-to-workspace-1|
|<Super>j|switch-to-workspace-down|
|<Super>l|switch-to-workspace-last|
|<Super>k|switch-to-workspace-up|
|<Alt>Tab|switch-windows|
|<Shift><Alt>Tab|switch-windows-backward|
|<Alt>f|toggle-fullscreen|
|<Alt>j|unmaximize|
#### [org/gnome/mutter/keybindings]
|<Alt>h|toggle-tiled-left|
|<Alt>l|toggle-tiled-right|
#### [org/gnome/mutter/wayland/keybindings]
#### [org/gnome/settings-daemon/plugins/media-keys]
|<Primary><Alt>l|screensaver|
|<Super>Return|terminal|

### Vimium Chrome Extension
[Web page](https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb?hl=en)

1. Install Vimium Chrome Extension.
2. On its setting page go ```Backup and Restore -> Restore -> select file 'vimium-options.json' from this dir```.




## Tools
### generate_readme
`generate_readme` create resulting README.md from READMEs of different parts.

