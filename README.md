Install this repo on
```
~/.config/nvim
```

Run the following command
```
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

Remeber to source the init files
```
:so
```

Sync Packages
```
PackerSync
```

#Commands generated

## BASIC
```
space pv = :Ex => this means go back to file Explorer
```

## FUZZY FINDER (Telescope)
```
space pf = find file [by default is space ff]
space ps = search word
<C-p> = control+p = find file excluding git ignore
```

## HARPOON
Tool to manage multiple files on shortcuts

```
<C-h...C-l> = switch from 1-4
<C-e> = opens quickmenu
space a = adds file to quickmenu
```

*NOTE*: You can modify the quickmenu as a text file, move lines around to change bindings.

## TREE SITTER
Coloring for project files based on language, it's really fast and light.

*NOTE*: Requires a C compiler (download gcc)

## UNDO TREE
It's a local version control for changes
```
space u = open up the tree.
```

*NOTE*: You can click on the * to go to a node or use <C-w> to enter window mode and move to the window with h. And press enter on the node to read it.

## VIM FUGITIVE
Gives the ability to check git status
```
space gs = brings a menu to check git status
```

## LSP ZERO
LSP for Snippets and Autocompletion
# nvim-configs
