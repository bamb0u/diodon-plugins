# Diodon Plugins
This is a set of plugins for the gnome clipboard manager Diodon.

- **Paste All**  
Simple plugin to paste all recent items at once, optionally appending a string to
the end (defaults to newline).

- **Sticky**  
Opens a window representation of the Diodon menu. The window will stay on top
and reflect changes to the clipboard. Allows search clipboard items.

## Installing

``` bash
git clone https://github.com/RedHatter/diodon-plugins.git
cd diodon-plugins
./waf configure && ./waf build && ./waf install
```

## Debuging

``` bash
G_MESSAGES_DEBUG=all diodon
```