# Vim Modes and Motions Cheat Sheet

This cheat sheet covers the most common modes and motions in Vim, helping you navigate and edit text efficiently.

## Modes

### Normal Mode
- Default mode
- Press `Esc` or `Ctrl+[` to enter

### Insert Mode
- Enter by pressing `i` (before cursor) or `a` (after cursor)
- Used for entering text

### Visual Mode
- Enter by pressing `v`
- Select text visually

### Command Line Mode
- Enter by pressing `:` followed by `q`

## Motions

### Deletion
- Delete entire line: `dd`
- Delete from cursor to end of line: `D` or `C`
- Delete from cursor to start of line: `d^` or `Ctrl+u` (in insert mode)

### Cutting
- Cut entire word: `ciw` or `ciW`
- Cut current line: `cc`

### Copying
- Copy entire word: `yiw` or `yiW`
- Copy current line: `yy`

### Pasting
- Paste after cursor: `p`

### Selection
- Select entire line: `V`

## Horizontal Movements

### Left Arrow
- Move left: `h`

### Right Arrow
- Move right: `l`

### Word Movement
- Next word: `w` or `W`
- Previous word: `b` or `B`
- Start of word: `b` or `B`
- End of word: `e` or `E`

### Deletion at Word Boundaries
- Delete current word: `diw` or `diW`
- Delete from before cursor to start of word: `db` or `dB`
- Delete from cursor to end or word: `dw` or `dW`
- Select current word: `viw` or `viW`
- Change current word: `ciw` or `ciW`
- Copy current word: `yiw` or `yiW`

### Deletion in Bracket Boundaries
- Delete everything in Parenthesis(): `dib`
- Delete everything with and between Parenthesis(): `dab`
- Delete everything in curly braces{}: `diB`
- Delete everything with and between curly braces{}: `daB`
- Delete everything in "": `di"`
- Delete everything with and between "": `da"`
- Change everything in Parenthesis(): `cib`
- Change everything with and between Parenthesis(): `cab`
- Change everything in curly braces{}: `ciB`
- Change everything with and between curly braces{}: `caB`
- Change everything in "": `ci"`
- Change everything with and between "": `ca"`

### Line Positioning
- Start of line: `I` or `_` (underscore)
- End of line: `A` or `$` (dollar-sign)

### Character Jumping
- Move to character: `f{char}` or `F{char}`
- Move just before character: `t{char}` or `T{char}`

## Additional Tips

- Press `.` to repeat last action
- Press `u` to undo last change
- Press `Ctrl+r` to redo last undone action

Remember, practice is key to mastering Vim. Start with these commands and gradually explore more advanced features as you become comfortable with the basics.
