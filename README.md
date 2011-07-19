# vim-jslint

## Requirements
* Node - [install](https://github.com/joyent/node/wiki/Installation)
* NPM
* jslint - npm install jslint -g
* [vim-pathogen](https://github.com/tpope/vim-pathogen)

## Installation
clone this repo into ~/.vim/bundles/
add the following to your .vimrc:

    nmap <F4> :w<CR>:make<CR>:cw<CR>

this saves then rus jslint

## Usage
1. open a js file and hit F4.
2. Fix your errors and repeat.

## Note
idea from: http://technotales.wordpress.com/2011/05/21/node-jslint-and-vim/
