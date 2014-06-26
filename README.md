Vimrc
=====

Features
--------

* very good documentation, almost every line of code is documented
* lots of useful key short-cuts, Macros, Commands etc. (see below)
* easily customizable
* custom status-line
* allows user-specific ~/.vimrc
* allows project specific vimrc ;)


Used Plugins
------------

* Spell
* Clang_Complete


Keymap
------

| Mode            | Keys              | Command                                                                   |
|-----------------|-------------------|---------------------------------------------------------------------------|
| n,i,v,c,o       | `Alt` + `Q`       | like `Esc`                                                                |
| n,i             | `Alt` + `W`       | format the current line at the 80th column                                |
| i               | `Alt` + `F`       | file completion, like `Ctrl` + `X`, `Ctrl` + `F`                          |
| n               | `Space`           | toggles between regular line numbering and hybrid mode                    |
| n               | `Tab`             | switch to next tab                                                        |
| n               | `Shift` + `Tab`   | switch to previous tab                                                    |
| n               | `Ctrl` + `P`      | same as `Ctrl` + `I` before remapping `Tab` (*not working*)               |
| n               | `Ctrl` + `N`      | creates a new, empty tab                                                  |
| n               | `Alt` + `N`       | splits the current window vertically and opens a file                     |
| i,c             | `F3`              | inserts the current time and date                                         |
| n               | `F8`              | removes all training whitespaces                                          |
| n               | `F9`              | toggle the tag list plugin window                                         |
| n               | `F12`             | prints compiler output, like `:cl`                                        |
| n               | `,t`              | opens the alternate file in a new tab                                     |
| n               | `,v`              | vertically splits the current window and opens the alternate file         |
| n               | `Alt` + `J`       | opens the tag list selection window                                       |
| v               | `*`               | forward search for the marked text                                        |
| v               | `#`               | backwards search for the marked text                                      |
