Here is my cheatsheet of random remaps or commands I want to remember
Note that my <leader> is " " (a space)

:! -> Lets you run terminal commands (e.g. :!python3 test.py)

$ -> Goto end of line
0 -> go to start of line
gg -> go to start of document
G -> go to end of document
xG -> go to line x
C-d/u -> go up/down a page while keeping cursor centered

"J"/"K" -> If highlighting lines, moves those lines up and down with indenting

o -> insert on new line below
O -> insert on new line above
I -> Insert at beginning of line
S -> Delete current line and enter insert
^ -> Move to first non-blank character of the line
a -> append at current cursor
A -> append at end of line

" Y" -> yanks current line to global clipboard
" y" -> in visual yanks selected lines to global clipboard

-------------------------------------
plugin specific
------------------------------------

" pf" -> Fuzzy finder (file navigation)
" pv" -> Go to directory
"C-p" -> Specific fuzzy finder for git files
" ps" -> Grep within git repo for a string

"C-e" -> Harpoon Menu
"C-{h,j,k,l}" -> Harpoon file {1,2,3,4}
" a" -> Add file to Harpoon

" u" toggle undo tree (this thing confuses me)
"C-w {h,j,k,l}" Move between split panes in vim  *useful for undotree

I have no clue how my lsp works. Wild...
