Having entered Batch Clipboard’s *batch mode* and copied some clipboard
items, each collected item will then be shown in the menu:

[[https://github.com/jpmhouston/Cleepp/blob/forkmain/Designs/Cleepp/Normal%20menu,%20with%20batch.png|alt=Batch In Progress Menu]]

The items remaining to paste are shows in the middle section of the Batch Clipboard menu.
The item at the top is the most recent copied, the item at the bottom,
badged with “replay from here” will be the one that is pasted next.

(macOS versions before 14.0 Sonoma had limited capability to add badged to
menu items. The item to be pasted next will simply be the one at the bottom
of the history.)

These menu items as also available when relevant:

- **Start Replaying Items** which will put the first item of the batch on
the clipboard. This is not commonly used because **Paste from Batch & Advance**
does this automatically before pasting the first item, however you should use it
if you want to paste this first item using your frontmost app's menu commands
(such as **Paste & Match Style**)

- **Cancel Batch** will cancel *batch mode* and return the clipboard
to its normal behavior, as mentioned in [[Menu Items]].

- **Copy to Batch** can be used to collect more clipboard items into the batch,
as mentioned in [[Menu Items]], however once in *batch mode* any normal
**Copy** or **Cut** command in the frontmost app will do the same as well.
Even if you've started to paste from the batch you can still collect more.
The default shortcut <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>
can be changed in the settings, see [[Settings]].

- **Paste from Batch & Advance** will instruct the frontmost app to paste the next
item from the batch and leave the subsequent item ready on the clipboard.
The default shortcut <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd>
can be changed in the settings, see [[Settings]].

- **Advance to Next Batch Item** is also not commonly used because
**Paste from Batch & Advance** does this automatically, however you can use this
if you've changed your mind and need to skip pasting an item, or have instead
pasted it using the frontmost app's command (such as **Paste & Match Style**).

- **Delete History Item** will remove the highlighted clipboard item from the
batch and the saved clipboard history. If it's the last item in the batch to be
pasted then it will also exit *batch mode* and return the clipboard to its
normal behavior. This item is available for use via its keyboard shortcut
<kbd>COMMAND (⌘)</kbd> + <kbd>DELETE (⌫)</kbd> when mousing over one of the
clipboard items, or having used arrow-keys to highlight it.

- **Clear History...** can be used to completely empty the saved clipboard
history including the current batch, exiting *batch mode* and returning the
clipboard to its normal behavior. The shortcut for this menu item,
<kbd>COMMAND (⌘)</kbd> + <kbd>OPTION (⌥)</kbd> + <kbd>DELETE (⌫)</kbd>
is not global and will only work when the Batch Clipboard menu is open.

—

Previous: [[Menu Items]]\
Next: [[Expanded Menu]]