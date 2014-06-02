time-lapse.vim
==============

A fork of [Vim Script #3849][vimscript]: "git-time-lapse : Perforce-style" by
Ben Cotterell

```vim
Bundle "johntyree/time-lapse.vim"
map <leader>gt :call TimeLapse() <cr> 
```

## Original README

### Description
You're editing a file which is in a git repository. Press a key which opens a
new tab which shows how that commit changed that file in Vim's diff mode (:help
diff), with a window at the bottom showing the commit message. Left and right
arrows move through the history. Shift-left and shift-right go all the way to
the end. Return on a line goes back to the last commit that touched that line
(using git blame).

Close the tab when you're bored with it and carry on Vimming as usual. You can
open as many time-lapse tabs on different files in one Vim session as you want.

Inspired by the "time lapse view" in the Perforce gui which I thought was quite
good, although I prefer the Vim version.


### Install details
Drop time-lapse.vim into .vim/plugin and map a key in your .vimrc, e.g.

map <leader>gt :call TimeLapse() <cr>

Or however you prefer.

You can also get the script with:

$ git clone http://www.tidraso.co.uk/repository/vim-plugin/

Where you may find new features.

[vimscript]: http://www.vim.org/scripts/script.php?script_id=3849

