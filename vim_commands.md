# VIM

## Basic movement: h, j, k, and l
*h* moves left
*j* moves down
*k* moves up					*9k* is the same as pressing k 9 times
*l* moves right

## Word movement: w, e, b
*w* moves to the start of next word; *3w* is the same as pressing w three times
*e* moves to the end of the word; 
*b* moves to beginning of the word. 

## Insert text repeatedly
*3ibabau Esc* inserts babau 3 times

## Find a character
*fo* finds next o
*3fq* finds the third q

## Go to matching parentheses
*shift %* to jump to matching (, {, [

## Go to start/end of line
*0* beginning of line
*$* end of line

## Find word occurrences
*``*``* next occurrence of the word under cursor (shift ``*``)
*``#``* previous occurrence of the word under cursor (Alt Gr ``#``)

## Go to beginning of file, line
*gg* takes you to the beginning of the file; 
*G* to the end
*2G* takes you to line 2

## Search text
*/* babau looks for babau occurrences
*n* searches the next occurrence
*N* searches the previous occurrence

## Insert new line
*o* inserts new line below and sets editor to insert mode
*O* inserts new line above and sets editor to insert mode

## Removing characters
*x* deletes the character under the cursor
*X* deletes the character to the left of the cursor

## Replacing letter under cursor
*r* new_character replace only one character under your cursor

## Deleting
*dw* deletes the first word on the right side of the cursor → you can paste it with *p* to another location
*d2e* deletes 2 words

## Repetition
*.* repeats the previous command

## Visual mode
*v* goes to visual mode, where you select text using movement keys before you decide what to do with it.

```
Goto visual mode with v.
Then select a word with e l.
After you've selected the text, you can delete it with d
```

## Undo / Redo / Help!
*u* for undo
*ctrl+R* for redo
*:help* for help ;)

## Buffers
*:ls* lists all buffers
*:b* 3 goes to buffer 3

## Split Layouts
*:sp* <filename> horizontal split
*:vp* <filename> vertical split

## Install plugins
*:PluginInstall*