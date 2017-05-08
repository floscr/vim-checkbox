

Vim Checkbox
============


Description
-----------

Simple plugin that toggles text checkboxes in Vim. Works great if you're using
a markdown file for notes and todo lists.

This fork uses the uppercase 'X' instead of 'x' which works better with [vimwiki]()


Installation
------------

Just copy the script into your plugin folder, e.g. `~/.vim/plugin/`.


Usage
-----

Type `<leader>tt` to toggle the (first) checkbox on the current line. A checkbox
is either `[ ]` (unchecked) or `[x]` (checked). For example,

    * [ ] Do some work.

becomes

	* [x] Do some work.

and vice versa.

[vimwiki]: https://github.com/vimwiki/vimwiki
