
# Editing Modes
* **Command mode**</br>
This is the default mode in which Vim starts. We can enter editor commands
in this mode. We can use variety of commands in this mode like copy, paste,
delete, replace and many more. We’ll discuss these commands in later
sections.
* **Insert mode**</br>
You can use this mode to enter/edit text. To switch from default command to
insert mode press i key. It will show current mode in bottom left corner of
editor. </br> </br>
Use Escape key to switch back to command mode from this mode.

* **Command line mode** </br>
This mode is also used to enter commands. Commands in this mode starts
with colon(:). For instance, in previous section quit command was entered in
this mode. We can go to this mode either from command or insert mode. </br>
To switch from command mode to this mode just type colon </br>
To switch from insert mode to this mode press Escape and type colon

* **Visual mode** </br>
In this mode we can visually select text and run commands on selected
sections. </br>
To switch from command mode to visual mode type v </br>
To switch from any other mode to visual mode first switch back to command
mode by pressing Escape , then type v to switch to visual mode


# Files
|Command| Description |
| ----- | ----------- |
| :edit <code>filePath</code> | reloads file if exists |
| :w               | writes to the file     |
| :q               | quits vim              |
| :q!              | quits vim without saving changes|
| :wq              | writes to the file and quits |

