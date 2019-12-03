# vim shortcuts
this is little doc for vim shortcut and tip/tricks utilizing vim. keep updating this doc.

## text objects
- w : words
- s : sentences
- p : paragraphs
- t : tags (available in XML/HTML files)

## motions
- a : all
- i : in
- t : 'til
- f : find forward
- F : find backward

## commands
- d : delete (also cut)
- y : yank (copy)
- c : change (delete, then enter insert mode)
- D/C : delete/change until end of line
- dd/yy : delete/yank the entire line
- v : visual select
- V : visual select entire line
- ^/$ : move to the beginning/end of line
- I/A : move to the beginning/end of line and enter insert mode
- o/O : insert new line below/above current line and enter insert mode
- p/P : paste below/above the current line
- h/j/k/l : left/up/down/right
- ^B/^F	: scroll up/down one page                    
- H/M/L	: move cursor to the top/middle/bottom of the window
- gg/G	: move to the top/bottom of the file

## basic command in use with motions and text objects
{command}{text object or motion}
example :
- diw : delete in word
- caw : change all word (including whitespaces) and enter insert mode
- yi) : yank in parentheses
- da[ : delete around brackest, including the brackets

## macro
### record a macro
1. q{register}
2. do the thing
3. q

### play a macro
@{register}

## some plugin that need to be looked up
- vundle	: plugin manager
- nerdtree	: file drawer
- ctrlp		: fuzzy file finder
- fugitive	: git tool
- syntastic	: syntax checker/linter
