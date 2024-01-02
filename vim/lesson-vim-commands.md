# VIM Commands

Command 	Description 	
i 	                Insert at cursor (goes into insert mode)
I 	                Insert at first non-whitespace character (goes into insert mode)
a 	                Write after cursor (goes into insert mode)
A 	                Write at the end of line (goes into insert mode)
ESC                Terminate insert mode
u 	                Undo last change
U 	                Undo all changes to the entire line
^R                   Redo last change
o 	               Open a new line below cursor line (goes into insert mode)
O 	               Open a new line above cursor line (goes into insert mode)
dd 	               Delete line
3dd                Delete 3 lines
D 	               Delete contents of cursor and whatever is after the cursor
C 	               Delete contents of a line after the cursor and insert new text. 
                       Press ESC key to end insertion.
dw 	               Delete word (word includes space after word)
4dw               Delete 4 words
cw 	              Change word (word doesn't include space)
x 	              Delete character at the cursor
r 	              Replace character
R 	             Overwrite characters from cursor onward
s 	             Substitute(delete) one character under cursor continue to insert
S 	             Substitute entire line and begin to insert at the 
                     beginning of the line
~ 	             Change case of individual character
ciw              Change innner word and go to Insert Mode (without spaces after)
diw              Delete inner word
ci'                Change inner 'everything in single quote' and go to Insert mode
di'                Delete inner 'everything in single quote'
ci"                Change inner "everything in double quotes" and go to Insert mode
di"                Delete inner "everything in double quotes"
ci(                Change inner "everything in ( )" and go to Insert mode
di(                Delete inner "everything in ( )"
>>                Tab cursor line to right side
<<                Tab cursor line to left side
2>>              Tab two lines to right
2<<              Tab two lines to left
gg               Go to first line of file
G                 Go to last line of file

ZZ               save document and quit (be careful!)
ctrl + y       to move the screen up one line
ctrl + e       to move the screen down one line
z + z           to move the current line I’m on to the center of the screen
z + t           to move the current line I’m on to the top of the screen
z + b          to move the current line I’m on to the bottom of the screen

  
***
Linux Command
https://www.guru99.com/linux-commands-cheat-sheet.html



