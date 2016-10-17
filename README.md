![Imgur](http://i.imgur.com/zPs92Hk.png)

# Pre-alpha Warning
This theme is in development stage and a lot of things need to be covered. Theme works only with [Neovim](https://neovim.io) and `termguicolors` option.

# Instalation
```VimL
Plug 'ayu-theme/ayu-vim' " or other package manager 
"...
colorscheme ayu
set background=light " for light version of theme
set background=dark  " for dark version of theme
```

# Term colors
For now In `/term` you can find color schemes for iTerm. More to come.

# Ident line
To get ident line like in the screenshot install https://github.com/Yggdroot/indentLine with my version of `Roboto Mono for Powerline` from this repo and add this config.
In this Roboto Mono version added powerline glyphs and increased line-height of the font itself.

```Viml
" IndentLine {{
let g:indentLine_char = ''
let g:indentLine_first_char = ''
let g:indentLine_showFirstIndentLevel = 1
let g:indentLine_setColors = 0
" }}
```
