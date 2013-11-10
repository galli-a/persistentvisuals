# `persistentvisuals`

Copy of the `persistentvisuals.vim` plugin by Damian Conway, to retain the visual selection after certain operations.

## Usage

The plugin can be used after a visual selection, when changin indentation:

	`>`, `<`  
 
when changing case:

	`~`, `L`, `U`

when joining lines:

	`J`
 
when substituting or replacing characters:

	`s`, `S`, `c`, `C`, `r`
 
when undoing or redoing: 

	`u`, `<C-R>`

Hit `<CR>` to escape from visual mode, and `ZZ` to quit directly from visual mode.
