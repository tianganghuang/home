set encoding=utf-8
set number
set cursorline
set incsearch
set wildmenu
set nocompatible
set laststatus=2
set timeoutlen=10 ttimeoutlen=0
set esckeys
colorscheme gruvbox

filetype off
filetype indent off
syntax on

" BEGIN VUNDLE 
set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()
Plugin 'gmarik/Vundle.vim'
Plugin 'vim-scripts/indentpython.vim'
Plugin 'Valloric/YouCompleteMe'
Plugin 'tpope/vim-surround'
" Plugin 'vim-airline/vim-airline'
Plugin 'itchyny/lightline.vim'
call vundle#end()
filetype plugin indent on
" END VUNDLE

" BEGIN VIMPLUG
" call plug#begin('~/.vim/autoload/plugged')

" call plug#end()
" END VIMPLUG

au BufNewFile, BufRead *.py
    \ set tabstop=4
    \ set softtabstop=4
    \ set shiftwidth=4
    \ set textwidth=79
    \ set expandtab
    \ set autoindent
    \ set fileformat=unix
au BufRead, BufNewFile *.py,*.pyw,*.c,*.h match BadWhitespace /\s\+$/

let g:ycm_path_to_python_interpreter = '/usr/bin/python3.11'
