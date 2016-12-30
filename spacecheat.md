# Spacemacs and Evil Mode Cheatsheet
## Evil Mode
### Movement
- `h` - move cursor left
- `j` - move cursor down
- `k` - move cursor up
- `l` - move cursor right
- `H` - move to top of screen
- `M` - move to middle of screen
- `L` - move to bottom of screen
- `w` - jump forwards to the start of a word
- `W` - jump forwards to the start of a word (words can contain punctuation)
- `e` - jump forwards to the end of a word
- `E` - jump forwards to the end of a word (words can contain punctuation)
- `b` - jump backwards to the start of a word
- `B` - jump backwards to the start of a word (words can contain punctuation)
- `0` - jump to the start of the line
- `^` - jump to the first non-blank character of the line
- `$` - jump to the end of the line
- `g_` - jump to the last non-blank character of the line
- `gg` - go to the first line of the document
- `G` - go to the last line of the document
- `5G` - go to line 5
- `fx` - jump to next occurrence of character x
- `tx` - jump to before next occurrence of character x
- `}` - jump to next paragraph (or function/block, when editing code)
- `{` - jump to previous paragraph (or function/block, when editing code)
- `Ctrl b` - move back one full screen
- `Ctrl f` - move forward one full screen
- `Ctrl d` - move forward 1/2 a screen
- `Ctrl u` - move back 1/2 a screen

## Spacemacs
### Buffers
- `SPC ff` - open new file in new buffer
- `SPC bb` - switch to buffer from list of available buffers
- `SPC bd` - kill current buffer
- `SPC bn` - switch to next buffer
- `SPC bp` - switch to previous buffer
### Windows
- `SPC <num>` - switch to window <num>
- `SPC wh` - switch to window to the left of current window
- `SPC wl` - switch to window to the right of current window
- `SPC wj` - switch to window below current window
- `SPC wk` - switch to window above current window

- `SPC w- ` - split window vertically
- `SPC w/` - split window horizontally
- `SPC wd` - kill current window
### Other Spacemacs Commands
- `SPC m` or `,`  - display major mode commands
- `SPC tn` - display line numbers in current buffer
- `SPC tr` - toggle between relative and absolute line numbers
- `SPC Tn` - cycle between available themes
- `SPC TS` - list available themes
