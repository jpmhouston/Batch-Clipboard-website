You may wish to collect into a batch with an application command other than
**Copy**, such as **Copy as Pathname** in the Finder, or of course **Cut**.
You may also with to paste using an application command other than **Paste**,
such as **Paste and Match Style**.

### Application Command Other Than Copy

As mentioned above and in [Beyond the Basics](Beyond-the-Basics.md), once
in _batch mode_ with the menu bar icon highlighted, anything copied normally
in your application will be added to the batch and increment the count in the
menu bar.

However, not only will a **Copy** command or <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>
in your frontmost application add to the batch, but also **Cut**, or any
special-purpose command that adds to the clipbaord. Any action that alters the
clipboard will be added to the batch, such as:

- a button on webpage that copies content to the clipboard,
- clipboard sharing from an iOS device.

### Application Command Other Than Paste

It's tricker, and arguably more awkward, to paste from a batch using an
application alternate Paste command, but possible. It requires turning on the
**Show advanced paste menu items** option in the Settings tab **Advanced**.
For more details see [Advanced Panel](Advanced-Panel.md).

Turning this on adds the menu item that is titled either
**Start Pasting From Batch** or **Skip to Next** depending on
circumstance. Using them can be illustrated by example ...

Firstly, if you are in the middle of replaying a batch and the next item
to paste you wish use your application's special-purpose command instead of
the keyboard shortcut <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd>
or **Paste & Advance** in the Batch Clipbaord menu.

Imortantly, when you are in the process of pasting from a batch then the
next clip to be pasted is already present on the system clipboard, and the
advanced paste menu item has the title **Skip to Next**. What to do is:

- Invoke your application's special-purpose paste command
- Use **Skip to Next**

Secondly, if instead you are collecting clips into a batch and then the first
of these you wish to paste using your application's special-purpose command.
In this case the next item to paste isn't already on the clipboard, because
while still collecting clips into the batch the clipboard contains the most
recent thing copied.

In this case the advanced paste menu item has the title
**Start Pasting From Batch**. What to do in this case is:

- Use **Start Pasting From Batch** (this places the next clip to paste from
the batch onto the system clipboard and the menu item is changed to **Skip to Next**)
- Invoke your application's special-purpose paste command
- Use **Skip to Next**

## A Mental Model (For Deep Thinkers)

You can think of Batch Clipbaord's copy keyboard shortcut, or **Copy Into Batch**
in its menu, as doing:

1. **Start Batch** if necessary
2. invoke your application's standard **Copy** command

And you can think of the paste keyboard shortcut, or **Paste & Advance** in
the menu, as doing:

1. **Start Pasting From Batch** if necessary
2. invoke your application's standard **Paste** command
3. **Skip to Next**
