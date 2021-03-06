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
* ### 5: <kbd>Esc</kbd> + `:syntax on` - Enables Syntax Highlight
* ### 6. <kbd>Esc</kbd> + `:set mouse=a` - Enables Mouse.

* ### 7: <kbd>Esc</kbd> + <kbd>y</kbd> - Yank
	* Copies text. Y can be upper or lowercase.
* ### 8: <kbd>Esc</kbd> + <kbd>p</kbd> - Paste
	* Pastes text.
* ### 9: <kbd>Esc</kbd> + <kbd>x</kbd> - Cut
	* Cuts text. X can be upper or lowercase.
* ### 10: <kbd>Esc</kbd> + <kbd>d</kbd> - Delete
	* Pressing lower case d twice will delete the current line of the cursor.
	* Presssing Uppercase D just once will delete text that comes after the cursor for that line.
* ### 11: <kbd>Esc</kbd> + <kbd>u</kbd> - Undo
	* Lowercase u. Undoes the changes. Just like popular text softwares like microsoft word, google docs and so on.
* ### 12: <kbd>Esc</kbd> + `:set number` - Enables line number
* ### 13: <kbd>Esc</kbd> + <kbd>/</kbd> + "word to search" - Search / Find:
	* Finds and searches a word or sentence.
	* <kbd>Esc</kbd> + <kbd>n</kbd> - Lowercase n searches the next occurrence.
	* <kbd>Esc</kbd> + <kbd>N</kbd> - Uppercase N searches the previous occurrence.
* ### 14: <kbd>Esc</kbd> + `:set hlsearch` - Enables search highlight
* ### 15: <kbd>Esc</kbd> + `:noh` - Disable search highlight
	* Removes highlight from words that are currently highlighted.
* ### 16: <kbd>Esc</kbd> + `:24` - Go to line
	* 24 in the above command is just a hypothetical number. But we would enter the line number that we want to go to.
* ### 17: <kbd>Esc</kbd> + `:set colorcolumn=24` - Set Margin
	* Will set margin at 24th character width.
* ### 18: While in  `-- INSERT --` <kbd>Ctrl</kbd> + <kbd>n</kbd>- Word Completion.
	* Gives autofill suggestions.
* ### 19: <kbd>Esc</kbd> + <kbd>Ctrl</kbd> + <kbd>v</kbd> - Muliple line selection
	* <kbd>Esc</kbd> + <kbd>Ctrl</kbd> + <kbd>v</kbd> - `-- VISUAL BLOCK` will appear in the left bottom section.
	* Press <kbd>j</kbd> or <kbd> :arrow_down_small:</kbd> as many times as many lines you want to make the changes on.
	* Press <kbd>Shift</kbd> + <kbd>i</kbd> or <kbd>I</kbd> - `-- INSERT --` will appear in the left bottom screen.
	* Type text.
	* Press <kbd>Esc</kbd> to implement the text in all lines.
* ### 20: <kbd>Esc</kbd> + `:%s/source/destination` - Search and replace
	* <kbd>Esc</kbd> + `:%s/source/destination/gc` - Searches and asks for confirmation for each replacement.
	* <kbd>Esc</kbd> + `:%s/source/destination` - Searches and replaces everything. Does not ask for confirmation.
	* <kbd>Esc</kbd> + `:7,10s/source/destination/gc` - Searches and replaces between lines 7 and 10. Asks for confirmation for each change.
