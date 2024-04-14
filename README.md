" Remap Escape
inoremap kj <Esc>

" Shift Movements
nnoremap <S-Up> :m-2<CR>
nnoremap <S-Down> :m+<CR>
inoremap <S-Up> <Esc>:m-2<CR>
inoremap <S-Down> <Esc>:m+<CR>xxx

" Movement in Insert Mode
inoremap <C-h> <Left>
inoremap <C-l> <Right>

" Disable arrow keys
nnoremap <Up> <Nop>
nnoremap <Down> <Nop>
nnoremap <Left> <Nop>
nnoremap <Right> <Nop>

" Auto Indent whole file (go to beginning, indent whole file, go back where you came from)
nnoremap <C-S-L> gg=G<C-O>

" Settings
set clipboard+=ideaput
set relativenumber
set number 

