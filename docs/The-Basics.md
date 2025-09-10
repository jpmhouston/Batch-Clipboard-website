Batch Clipboard is a menu that lives in on the right side of the menubar, its icon is a little clipboard
with an asterisk on it: ![Icon](img/menu-icon-normal.png)

More about menubar icon here: [Menu Icon States](Menu-Icon-States.md).

The app’s core feature is to let you copy multiple items from one document,
then switch to another document and paste those items in the order you copied them.

It’s simple to use, here’s how:

1. In your source document copy using the special Batch Clipboard keyboard shortcut
<kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>.

    *The menu bar icon will highlight and get a number 1 added beside it.*

2. Repeat.

    *The number in the menu bar icon will increment with each item copied.
	You can copy items from any document in any app, they don’t have to be
	from the same place.*

3. In your target document paste using the special Batch Clipboard keyboard shortcut
<kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd>.

	  *The **first** thing you copied will be the first thing pasted.
	The clipboard will automatically advance to the next one
	and the number in the menu bar icon will decrement.*

4. Repeat.

	  *When all copied items have been pasted the menu bar icon will
	return to normal, copying and pasting will return to the normal behavior.*

So: instead of **Copy**, switch windows, **Paste**, switch _back_, **Copy**, switch windows _again_, **Paste**, ...

It's: **Copy**, **Copy**, ... switch windows _once_, **Paste**, **Paste** ... using the normal keyboard shortcuts plus the <kbd>CONTROL (^)</kbd> key.
