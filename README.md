## Window Management

### Creating and Closing Splits
- `:sp [file]`: Split the window horizontally and optionally open a specified file.
- `:vsp [file]`: Split the window vertically and optionally open a specified file.
- `Ctrl+w c`: Close the current split window.
- `Ctrl+w o`: Close all other split windows except the current one.

### Resizing Splits
- `Ctrl+w =`: Make all split windows equal in size.
- `Ctrl+w +`: Increase the height of the current window.
- `Ctrl+w -`: Decrease the height of the current window.
- `Ctrl+w >`: Increase the width of the current window.
- `Ctrl+w <`: Decrease the width of the current window.

### Moving Between Splits
- `Ctrl+w h`: Move to the left split.
- `Ctrl+w j`: Move to the split below.
- `Ctrl+w k`: Move to the split above.
- `Ctrl+w l`: Move to the right split.
- `Ctrl+w t`: Move to the top-left split.
- `Ctrl+w b`: Move to the bottom-right split.
- `Ctrl+w w`: Move to the next split (cycle through splits).

## Tab Management

### Creating and Navigating Tabs
- `:tabnew [file]`: Open a new tab and optionally open a specified file.
- `:tabc`: Close the current tab.
- `:tabo`: Close all other tabs except the current one.
- `gt` or `:tabn`: Go to the next tab.
- `gT` or `:tabp`: Go to the previous tab.
- `:tabfirst`: Go to the first tab.
- `:tablast`: Go to the last tab.
- `:tabm [N]`: Move the current tab to the Nth position (0-indexed).

### Managing Tab Pages
- `:tabs`: List all open tabs.
- `:tabdo [command]`: Execute a command in all tabs. For example, `:tabdo w` will save all open files in all tabs.


## Basic Navigation
- `h`, `j`, `k`, `l`: Move left, down, up, right
- `w`: Move to the beginning of the next word
- `b`: Move to the beginning of the previous word
- `e`: Move to the end of the word
- `0`: Move to the beginning of the line
- `$`: Move to the end of the line
- `gg`: Move to the beginning of the file
- `G`: Move to the end of the file
- `Ctrl+o`: Jump back to the previous cursor position
- `Ctrl+i`: Jump forward to the next cursor position

## Editing
- `i`: Enter insert mode before the cursor
- `a`: Enter insert mode after the cursor
- `o`: Open a new line below the current line and enter insert mode
- `O`: Open a new line above the current line and enter insert mode
- `x`: Delete the character under the cursor
- `dw`: Delete from the cursor to the end of the word
- `dd`: Delete the current line
- `cw`: Change (delete and switch to insert mode) until the end of the word
- `cc`: Change the entire line
- `yy`: Yank (copy) the current line
- `p`: Paste after the cursor
- `P`: Paste before the cursor
- `u`: Undo
- `Ctrl+r`: Redo

## Visual Mode
- `v`: Start visual mode (character-wise)
- `V`: Start visual mode (line-wise)
- `Ctrl+v`: Start visual mode (block-wise)

## Search and Replace
- `/`: Search forward for a pattern
- `?`: Search backward for a pattern
- `n`: Move to the next occurrence in the search
- `N`: Move to the previous occurrence in the search
- `:%s/old/new/g`: Replace all occurrences of "old" with "new" in the file
