# My NVIM Setup

I've always wanted to learn how to use Vim, but I never really took the time to do it.
So, here it is. I'm learning and loving it. 

Here are the plugins that I use:

 - Packer
 - Telescope
 - Kanagawa Wave Colorscheme
 - Treesitter
 - Treesitter Playground
 - Harpoon
 - Undotree
 - Vim-fugitive
 - LSP Zero
 - NERDTree

There are some custom key bindings configured too:

 - `space`pv: get back to file explorer
 - J or K in Visual Mode: move around the selected lines
 - `space`y: yank the selected lines to the OS clipboard so they can be pasted elsewhere
 - Q: is mapped to nop just in case
 - `space`s: to replace every occurence of the current word that the cursor is selecting
 - `space`x: chmod +x the current file
 - `space`ff: find files using Telescope
 - Ctrl+p: find git files using Telescope
 - `space`ps: find string occurances in all the files using Telescope
 - Ctrl+m: Open/Jump to NERDTreeFind
 - `space`a: add file to Harpoon
 - Ctrl+e: toggle Harpoon menu
 - Ctrl+h: navigate to the first file saved on Harpoon
 - Ctrl+t: navigate to the second file saved on Harpoon
 - Ctrl+n: navigate to the third file saved on Harpoon
 - Ctrl+s: navigate to the fourth file saved on Harpoon
 - `space`gs: opens Git from Vim-fugitive
 - `space`u: toggle the Undotree

 Feel free to fork it and edit it your way. Most of those configurations I learned from 
 [ThePrimeagen](https://www.youtube.com/watch?v=w7i4amO_zaE). If you want to learn how to
 use Vim, I really recommend watching his videos. 
