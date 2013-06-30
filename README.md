# Bare Bones Vim

Finding your way around without plugins or (too much) vimrc.

This is a talk given by Kris Jenkins at Vim London, 30/4/2013, for the
'Navigating a Codebase' night.

[You can watch it here.](https://vimeo.com/65250028)

## In conclusion.

`:find` is your friend, especially if you:

```vim
set path=**
set suffixesadd=.java,.py
set nocompatible
set wildmode=full
set wildmenu
set wildignore=*.class,*.pyc
```

`:ls` and `:<number>b` help too.

`:Explore` and `:e scp://host/some/where/file.txt` are must-know options.
