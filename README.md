Pull all submodules
====================
git submodule foreach git pull

add submodule:
===============
  git submodule add git://gitxxxx.git vim/bundle/name
  git submodule init

jj is used instead of escape in insert mode

nmap <leader>l <ESC>:TagbarToggle<cr>
imap <leader>l <ESC>:TagbarToggle<cr>i

use leader+t to tag current directory and add map it
map <leader>t: <f4> set tags+=./tags

set pastetoggle=<F3>

Fix White space
==============
:FixWhitespace

vim grep operator
================
viw<leader>g: Visually select a word, then grep for it.
<leader>g4w: Grep for the next four words.
<leader>gt;: Grep until semicolon.

Compview
=========
Mapped Keys: <Leader>v   Begin a search.
type '\c' without the quotes to do a case insensitive
TaskList:
leader-d to show Tasklist

q Quit and restore cursor
e Exit butkeep results window
cr> - Quit and place the cursor on the selected line.

ConqueTerm
===========
:ConqueTerm bash

NerdCommenter
=============
use leader then corresponding command
mode, use, command
'nx', 'Comment', 'cc'
'nx', 'Toggle', 'c<space>'
'nx', 'Minimal', 'cm'
'nx', 'Nested', 'cn'
'n',  'To EOL', 'c$'
'nx', 'Invert', 'ci'
'nx', 'Sexy', 'cs'
'nx', 'Yank then comment', 'cy'
'n',  'Append', 'cA'
'nx', 'Left aligned', 'cl'
'nx', 'Left and right aligned', 'cb'
'nx', 'Uncomment', 'cu'
'n',  'Switch Delimiters', 'ca'
'i',  'Insert Comment Here', ''

Command-T
=========
  <Leader>f     bring up the Command-T file window
  <Leader>b     bring up the Command-T buffer window

    <BS>        delete the character to the left of the cursor
    <Del>       delete the character at the cursor
    <Left>      move the cursor one character to the left
    <C-h>       move the cursor one character to the left
    <Right>     move the cursor one character to the right
    <C-l>       move the cursor one character to the right
    <C-a>       move the cursor to the start (left)
    <C-e>       move the cursor to the end (right)
    <C-u>       clear the contents of the prompt
    <Tab>       change focus to the file listing

The following mappings are active when the file listing has focus:

    <Tab>       change focus to the prompt

The following mappings are active when either the prompt or the file listing
has focus:

    <CR>        open the selected file
    <C-CR>      open the selected file in a new split window
    <C-s>       open the selected file in a new split window
    <C-v>       open the selected file in a new vertical split window
    <C-t>       open the selected file in a new tab
    <C-j>       select next file in the file listing
    <C-n>       select next file in the file listing
    <Down>      select next file in the file listing
    <C-k>       select previous file in the file listing
    <C-p>       select previous file in the file listing
    <Up>        select previous file in the file listing
    <C-f>       flush the cache (see |:CommandTFlush| for details)
    <C-c>       cancel (dismisses file listing)

Snipmate
========
 use snippets then tabs
for c:
 main
 void main mainn
 <> include inc
 "" include Inc
 ifndef def Def
 def
 ifdef
 #if
 #ifnded #define header once
 if
 else el
 ternary op t
 do
 wh
 for
 forr
 func imp fun
 func def fund
 typedef td
 struct st
 typedef struct tds
 typedef enum tde
 printf pr
 fprintf fpr

===========
To be continued









