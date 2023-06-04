# i3wm Cheatsheet

`$mod` refers to the modifier key

* `Alt` key by default - `Mod1`
* `Super ⌘` or `Win` could be an alternative - `Mod4`

Replace in `~/.config/i3/config` to change the modifier key

```
set $mod Mod4
```

## Basics

* `mod + Enter`     open new terminal
* `mod + j` 	focus left
* `mod + k` 	focus down
* `mod + l` 	focus up
* `mod + ;` 	focus right
* `mod + a` 	focus parent
* `mod + Space` 	toggle focus mode

### Moving Windows
* `mod + Shift + j` 	move window left
* `mod + Shift + k` 	move window down
* `mod + Shift + l` 	move window up
* `mod + Shift + ;` 	move window right

### Modifying windows
* `mod + f` 	toggle fullscreen
* `mod + v` 	split a window vertically
* `mod + h` 	split a window horizontally
* `mod + r` 	resize mode

### Changing the container layout
* `mod + e` 	default
* `mod + s` 	stacking
* `mod + w` 	tabbed

### Floating
* `mod + Shift + Space` 	toggle floating
* `mod + Left click` 	drag floating

### Using workspaces
* `mod + 0-9` 	switch to another workspace
* `mod + Shift + 0-9` 	move a window to another workspace

### Opening applications / Closing windows
* `mod + d` 	open application launcher (dmenu)
* `mod + Shift + q` 	kill a window