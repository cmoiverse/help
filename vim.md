#Vim
a - curr position
A - END
i - before currently position
I - beginning
o - new line after current line
O - new line before current line

j - up
k - down
h - left
l - right

^ - ctrl
^F - forward one screen
^B - backward one screen
^U - back half screen
^D - forward half screen
^f - forward 1 page
^b - backwards 1 o=page

w - 1 word to the right
b - 1 word to the left

ZZ - :wq + enter
:q! - quit & don’t save
x - delete char
dw - delete forward from cursor
dxw - delete x consecutive words
db - delete backwards from cursor
dd - delete line -> D, d$
d^ - delete to end of line
xdd - delete x lines

yy - yank current line
xyy - yank x lines
y$ - yank to end of current line from cursor
yw - yank from cursor to end of word

p - paste below
P - paste above
u - undo last change
^r - redo
U - restore line
J - join next line down to end of current line

:w - write workspace to original file
:w file - write workspace to named file
:e file - start editing a new file
:r file - read contents of a file to workspace

cw - make current word new word
R - replace mode
:r - replace 1 char at cursor position

:/pattern - search forward for pattern
:? - backward
n - find next occurrence of pattern

$ - line end
0 - line beginning 

:g/pat1/s//pat2/g - replace pattern1 with pattern2
:g/a/s// /g - replace a by blank
:g/a/s///g - replace a by nothing
