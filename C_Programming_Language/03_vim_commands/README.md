# Basic Vim Commands

* ### 1: <kbd>I</kbd> - Insert Mode.
	* `-- INSERT --` will appear at the bottom left of the window. Allows the user to enter text. 
	* One more test.
* ### 2:<kbd>Esc</kbd> or <kbd>Ctrl</kbd> + <kbd>c</kbd>: Escape Mode
	* Allows the user to enter addtional commands to perform further actions.
* ### 3: <kbd>Esc</kbd> + <kbd>:</kbd> + <kbd>w</kbd> - Saves file
	* Allows the user to save file. w has to be lowercase.
* ### 4: <kbd>Esc</kbd> + <kbd>:</kbd> + <kbd>q</kbd> - Closes file
	* Allows the user to exit out of file. q has to be lowercase.
	* <kbd>Esc</kbd> + <kbd>:</kbd> + <kbd>w</kbd> + <kbd>q</kbd> - Allows the user to save the file and then exit out of it.
* ### 5: <kbd>Esc</kbd> + <kbd>y</kbd> - Yank
	* Copies text. Y can be upper or lowercase.
* ### 6: <kbd>Esc</kbd> + <kbd>x</kbd> - Cut
	* Cuts text. X can be upper or lowercase.
* ### 7: <kbd>Esc</kbd> + <kbd>p</kbd> - Paste
	* Pastes text.
* ### 8: <kbd>Esc</kbd> + <kbd>d</kbd> - Delete
	* Pressing lower case d twice will delete the current line of the cursor.
	* Presssing Uppercase D just once will delete text that comes after the cursor for that line.
* ### 9: <kbd>Esc</kbd> + <kbd>u</kbd> - Undo
	* Lowercase u. Undoes the changes. Just like popular text softwares like microsoft word, google docs and so on.
* ### 10: <kbd>Esc</kbd> + <kbd>/</kbd> + "word to search" - Search / Find:
	* Finds and searches a word or sentence.
	* <kbd>Esc</kbd> + <kbd>n</kbd> - Lowercase n searches the next occurrence.
	* <kbd>Esc</kbd> + <kbd>N</kbd> - Uppercase N searches the previous occurrence.
* ### 11: <kbd>Esc</kbd> + <kbd>:</kbd> + `noh` - No highlight
	* Removes highlight from words that are currently highlighted.
* ### 12: <kbd>Esc</kbd> + <kbd>:</kbd> + `24` - Go to line
	* 24 in the above command is just a hypothetical number. But we would enter the line number that we want to go to.
* ### 13: <kbd>Esc</kbd> + <kbd>:</kbd> + `set colorcolumn=24` - Set Margin
	* Will set margin at 24th character width.
* ### 14: <kbd>Esc</kbd> + <kbd>Ctrl</kbd> + <kbd>v</kbd> - Muliple line selection has a few steps
	* <kbd>Esc</kbd> + <kbd>Ctrl</kbd> + <kbd>v</kbd> - `-- VISUAL BLOCK` will appear in the left bottom section.
	* Press <kbd>j</kbd> or <kbd> :arrow_down:</kbd>
