# tmux commands

*All commands are prefaced by `C-b`.*

## Standard Commands

### Sessions

* `s`   select new session
* `L`   switch to previous session
* `d`   detach
* `$`   rename session


### Windows

#### Management

* `c`   create window
* `&`   kill window
* `,`   rename window
* `!`   break pane from window
* `.`   move window to index

#### Navigation

* `w`   switch to window interactively
* `'`   switch to window index
* `0` to `9` select window at index
* `l`   previously selected window

**Disabled in favor of `C-n` and `C-p`**
* `n`   next window (`M-n` for next window with active bell)
* `p`   previous window (`M-p` for previous window with active bell)


### Panes

#### Management

* `"`   horizontal split
* `%`   vertical split
* `x`   kill pane

* `{`/`}` swap the current pane with the previous/next pane
* `M-1` to `M-5` arrange panes in various ways

* `C-`*arrow key* --- resize current pane  (`M-`*arrow key* for larger step sizes)

#### Navigation

* `o`   next pane
* `;`   previously active pane
* `q`   show pane indexes

*  *arrow key* --- navigate panes visually, relative to current pane


### Other

* `[`   enter copy mode
* `]`   paste most recently copied text
* `#`   list paste buffers
* `f`   find text
* `t`   show the time
* `?`   help


## Custom Commands

Join panes (opposite of `!` breaking behavior)
* `j`    send pane to location
* `C-j`  join pane from location
