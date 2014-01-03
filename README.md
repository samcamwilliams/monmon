monmon
======

monmon is the monitor monitor - it monitors when monitors are (un)plugged and performs appropriate actions. I have it configured to extend the desktop across 2 screens when one is plugged in, then remove the extra desktop when the monitor is removed. It is incredibly small (30 lines) and uses Erlang, xrandr and nitrogen (for restoring wallpapers - easily removable).

## Usage ##

Configure the program as you wish. You will probably want to change the xrandr commands. Execute monmon in your `.xinitrc`.

## Future Work ##

* Generalise. Make it into a very small version of 'IfThisThenThat' for the linux desktop.
* Modularise it.
