# Gruber Darker Theme

The original Gruber Darker Theme is an emacs theme located [here](https://github.com/rexim/gruber-darker-theme).
This is an in progress theme. Currently, It has bindings that really only work
for Haskell and python. Java is annoying and it depends on your ```.vimrc```.
I am adding theming as I use certain files.

## Notes

The theme supports 256 color vim versions. However, it will be more accurate if
you are using Nvim or a newer Vim and using ```set termguicolors```.

## Install

Using vim-plug:
1) Inside ```.vimrc``` or ```init.vim``` import this: ```Plug 'dangerousScript/gruber-darker-nvim'```
2) Install added plugin via ```:PlugInstall```
3) To enable theme, use this in ```.vimrc``` or ```init.vim``` after ```call plug#end()```:
  - ```set termguicolors``` below this add: ```colorscheme gruberdarker```
  
