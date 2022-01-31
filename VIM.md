# VIM

this file has vim hacks.

# nice setup for Yaml

All sorts of nice things to put into your .vimrc:

```
syntax on
colo default
autocmd BufRead,BufNewFile *.adoc   set filetype=asciidoc
" YAML config"
au! BufNewFile,BufReadPost *{yaml,yml} set filetype=yaml foldmethod=indent
autocmd FileType yaml setlocal ts=2 sts=2 sw=2 et ai
hi colorcolumn guibg=#444444
hi colorcolumn ctermbg=235
```
