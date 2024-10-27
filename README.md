# Vim Cheat Sheet

This cheat sheet covers the most common modes and motions in Vim, helping you navigate and edit text efficiently.

## Modes

### Normal Mode
- Default mode
- Press `Esc` or `Ctrl+c` or `Ctrl+[` to enter

### Insert Mode
- Enter by pressing `i` (before cursor) or `a` (after cursor)
- Used for entering text

### Visual Mode
- Enter by pressing `v`
- Select text visually

### Command Line Mode
- Enter by pressing `:` followed by `q`

## Operations/Motions

- Delete: `d`
- Change: `c`
- Select: `v`
- Copy/Yank: `y`
- Cut: `x`
- Paste: `p`

## Horizontal Movements

### Left Arrow
- Move left: `h`

### Right Arrow
- Move right: `l`

### Word Movement
- Next word: `w` or `W` (with pancuation)
- Previous word: `b` or `B` (with pancuation)
- Start of word: `b` or `B` (with pancuation)
- End of word: `e` or `E` (with pancuation)

### Line Positioning
- Start of line: `I` or `_` (underscore)
- End of line: `A` or `$` (dollar-sign)

### Operations within words
- Delete entire word: `diw` or `diW` (with pancuation)
- Delete from before cursor to start of word: `db` or `dB` (with pancuation)
- Delete from cursor to end or word: `dw` or `dW` (with pancuation)
- Change entire word: `ciw` or `ciW` (with pancuation)
- Copy(Yank) entire word: `yiw` or `yiW` (with pancuation)
- Select(Visual) entire word: `viw` or `viW` (with pancuation)

### Character Jumping
- Move to character: `f{char}` or `F{char}`
- Move just before character: `t{char}` or `T{char}`
- Delete upto an specific character (?): `df?` or `dF?`
- Delete upto just before of an specific character (!): `dt!` or `dT!`
- Change upto an specific character (?): `cf?` or `cF?`
- Change upto just before of an specific character (!): `ct!` or `cT!`
- Find same character in line: `;` or `,`

### Operations within lines
- Delete entire line: `dd`
- Copy entire line: `yy`
- Change entire line: `cc` or `S`
- Select entire line: `V`
- Duplicate entire line: `yyp` or `Yp`
- Delete from cursor to end of line: `D` or `C`
- Delete from cursor to start of line: `d^` or `c^` or `Ctrl+u` (in insert mode)

## Vertical Movements:

### Up Arrow
- Move Up: `k`
- jump 8 line up: `8k`
- Delete above 5 line: `d5k`

### Down Arrow
- Move down: `j`
- jump 10 line below: `10j`
- Delete below 3 line: `d3j`

### Operations with lines
- Move to the top of a file: `gg`
- Move to the end of a file: `G`
- Move cursor at the middle: `zz`
- Insert a new line above cursor: `O`
- Insert a new line below cursor: `o`

## Operations in Bracket Boundaries

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
- Remove struct/class/function with declaration: `vaBVd` or `vaBVc`
- Change everything in "": `ci"`
- Change everything with and between "": `ca"`
- Jumping to matching bracket: `%`
- Move to start of brakets: `[(`, `[{`
- Move to end of brakets: `])`, `]}`

## Additional Tips

- Press `.` to repeat last action
- Press `u` to undo last change
- Press `Ctrl+r` to redo last undone action

Remember, practice is key to mastering Vim. Start with these commands and gradually explore more advanced features as you become comfortable with the basics.
