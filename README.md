Homesick castle tmux
=====================

This is a [homesick](https://github.com/technicalpickles/homesick) _castle_ for [tmux](http://tmux.sourceforge.net/).


Cheat Sheet
=============

Control character: ```C-a```(Control+a). ```C-a``` ```C-a``` ("double C-a") is passed through to the shell.

Navigation
-------------

* ```C-a``` ```n``` : Next window
* ```C-a``` ```p``` : Previous window


* ```C-a``` ```h``` : Pane left
* ```C-a``` ```l``` : Pane right
* ```C-a``` ```k``` : Pane up
* ```C-a``` ```j``` : Pane down

Management of panes/windows
----------------------------

* ```C-a``` ```c``` : Create window
* ```C-a``` ```-``` : Split horizontally
* ```C-a``` ```|``` : Split vertically

* ```C-a``` ```UP``` : Move the current pane into a new window _tmp_ and activate it ("maximize"). A placeholder pane is created instead of the maximized pane. This is destroyed afterwards.
* ```C-a``` ```DOWN``` : Move the _tmp_ window back in place.

* ```C-a``` ```H/L/K/J``` : shift-movement keys will resize panes
* ```C-a``` ```SPACE``` : Cycle different pane layouts

* ```C-a``` ```,``` : Set window title

Copy/Paste
-----------

* ```C-a``` ```ESC``` : Start copy mode
* ```C-a``` ```P``` : Paste

**In copy mode**:

* ```v``` : start select
* ```RETURN``` : end select & copy
