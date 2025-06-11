Clicking the Batch Clipboard menu icon with <kbd>OPTION (⌥)</kbd> pressed
will show the expanded menu which also includes recent history of everything
on the clipboard:

[[https://github.com/jpmhouston/Cleepp/blob/forkmain/Designs/Cleepp/Expanded%20menu.png|alt=Expanded Menu]]

When in *batch mode*, the item to be pasted next
will probably not be at the very bottom but will still be indicated by the
badge "replay from here". There will also be a separator line between this and
the earlier clipboard items below it. (When running macOS versions before
14.0 Sonoma, this item won't get this badge but still have a separator line)

What you can do with the expanded history items:

- To see the larger preview of the text or image of a history item, mouse over,
or use arrow-keys to highlight it, and wait a couple of seconds for the tooltip
to appear.

- To replay pasting a clipboard item, select that item. It will be placed on the
clipboard and you can use your application's normal Paste command to paste it.

- You can delete a history item. Mouse over, or use arrow-keys to highlight it,
then press <kbd>COMMAND (⌘)</kbd> + <kbd>DELETE (⌫)</kbd>.

The expanded menu also adds this menu item:

- **Delete History Item** is available for use via its keyboard shortcut
<kbd>COMMAND (⌘)</kbd> + <kbd>DELETE (⌫)</kbd> when mousing over one of the
clipboard items, or having used arrow-keys to highlight it.

- **Clear History...** use this menu item to completely empty the saved
clipboard history. If currently in *batch mode*, then all such items
will also be cleared and clipboard behavior will return to normal.
The shortcut for this menu item,
<kbd>COMMAND (⌘)</kbd> + <kbd>OPTION (⌥)</kbd> + <kbd>DELETE (⌫)</kbd>
is not global and will only work when the Batch Clipboard menu is open.\
\
    *If you're wanting to delete a record of sensitive data you may have copied,
consider instead temporarily pausing the app’s monitoring of the clipboard
beforehand, see [[Special Menu Icon Actions]] and [[Ignore Custom Copy Types]].*

The number of history items displayed in the menu can be changed in the settings
window, see [[Settings]].

---

Previous: [[Batch Mode Menu Items]]\
Next: [[Settings]]