search documentation of cursor work (by pressing `K`) in xrepl, not browser. to make it work, you need to

+ put something like this `echo ",describe $1" | racket | grep -e "^[;>]"` in a text file
+ name that file racketdoc
+ make it executable: `chmod u+x racketdoc`

> # vim-racket
>
> Installation
> ------------
>
> This module works with many Vim plugin managers. To use with pathogen, type the following into a terminal:
>
>     cd ~/.vim/bundle
>     git clone https://github.com/wlangstroth/vim-racket.git
>
> Re-open your file(s) and benefit from the features of _vim-racket_.
>
> ## Thanks
>
> Most of the real work on this module was done by [Paul Cannon](https://github.com/thepaul) and [Asumu Takikawa](https://github.com/takikawa).
>
> To see all the contributors,
>
>     git log | grep ^Author: | sed 's/ <.*//; s/^Author: //' | sort | uniq -c | sort -nr
