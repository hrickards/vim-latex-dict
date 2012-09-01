Dictionaries copied from vim-latex

To install, use vundle and put `Bundle 'hrickards/vim-latex-dict'` into vimrc.

To use, do something like this in vimrc:
    autocmd filetype tex setlocal dictionary+=$HOME/.vim/bundle/vim-latex-dict/dict/dictionary
    autocmd filetype tex setlocal dictionary+=$HOME/.vim/bundle/vim-latex-dict/dict/SIunits
    set complete+=k
