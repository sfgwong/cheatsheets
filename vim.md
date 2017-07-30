# Cursor
* `^` - first non-blank character of line (same as 0w)
* `$` - end of line
* `gg` - go to the top of the page
* `G` - go the bottom of the page

# Edit
* `i` - start insert mode at cursor
* `I` - insert at the beginning of the line
* `a` - append after the cursor
* `A` - append at the end of the line
* `v` - starts visual mode
* `u` - undo
* `Ctrl+r` - redo
* `.` - repeat last command

# Cut and Paste
* `yy` - yank (copy) a line
* `p` - put (paste) the clipboard after cursor
* `dd` - delete (cut) a line
* `x` - delete (cut) current character
* `X` - delete previous character (like backspace)

# Exiting
* `:w` - write (save) the file, but don't exit
* `:wq` - write (save) and quit
* `:q` - quit (fails if anything has changed)
* `:q!` - quit and throw away changes

# Search/Replace
* `/pattern` - search for pattern
* `?pattern` - search backward for pattern
* `n` - repeat search in same direction
* `N` - repeat search in opposite direction
* `:%s/old/new/g` - replace all old with new throughout file ([gn](https://github.com/vinitkumar/white-paper) is better though)
* `:%s/old/new/gc` - replace all old with new throughout file with confirmations

# Files
* `:e filename` - Edit a file
   
main reference: https://github.com/theicfire/vimsheet/blob/gh-pages/index.md
