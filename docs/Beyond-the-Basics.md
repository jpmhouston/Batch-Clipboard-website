## About Batch Mode

When using the Batch Clipboard keyboard shortcut
<kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>
the clipboard enters a new _batch mode_ where items you have copied get
stored. This first item you've copied, and each item copied after that,
can be seen in a section of the Batch Clipboard menu called "Active Batch".

Whenever you're in _batch mode_ a count appears beside the Batch Clipboard icon
in the menu bar.

When you have a clipboard items stored, using
<kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd>
will paste them one-at-a-time replayed in the same order you copied them.
After you paste all the items in the batch, the clipboard returns to
normal.

> So only use Batch Clipboard's special keyboard shortcuts when you're copying
and pasting a batch of items, _batch mode_ is not meant to be left on.

> _If you've pasting some of the items from the batch but not all, leaving_
batch mode _still on, then the clipboard may behave somewhat unexpectedly:
if you copy something new, using **Paste** in the frontmost application will
not paste that, but instead the next item in the batch._

> _However if you started batch mode but hadn't yet pasted from it, then 
the clipboard will function similar enough to normal that you might not notice.
If you happen to glance in the menu bar and notice a large count beside the
Batch Clipboard menu unexpectedly, then you've done this, left_ batch mode
_on. That's okay, it's easy to go back to normal..._

You may wish to cancel _batch mode_ if you've changed you mind about pasting
some or all of the items you copied. Cancelling is done with the **Cancel Batch**
menu item (or a quicker way, see below). See also [Menu Items](Menu-Items.md).

> _But if you've decided you've copied the wrong thing when accumulating clips
into a batch, you_ don't _necessarily need to cancel and start all over. It_
is _possible to delete an item from the batch, see
[Batch Mode Menu Items](Batch-Mode-Menu-Items.md)._

Also, while in _batch mode_ and after you've started pasting from the batch,
it's fine to copy more items. Those items copied will get added to the end
of the batch, becoming the last items to paste.

## Behind The Curtain

Once you're already in _batch mode_, any change to the system clipboard is
seen by Batch Clipboard. This means you don't need to keep using the global
shortcut <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>,
you really only use that shortcut for the first clipboard item which enters
_batch mode_ and copies the selection as the first thing in the batch.

This means using **Cut** from the frontmost application will also add this
to the active batch, and also right clicking a selection and choosing
**Cut** or **Copy**, or any other feature of an application that adds to
the system clipboard.

> The same is not true for pasting however. You **do** need to use either
the Batch Clipboard keyboard shortcut
<kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd>
(or the **Paste from Batch & Advance** menu item) to paste from the batch
and automatically advance to the next item.

You may _choose to_ the use this keyboard shortcut for each clip however
(we at Bananameter Labs usually do) because it follow a nice symmetrical
and memorable mental model:

- <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd> to copy into
a batch,
- <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd>
to paste from it.

For tips and techniques to using the frontmost application's copy and paste
commands with Batch Clipboard, see [Advanced Copy and Paste Techniques](Advanced-Copy-and-Paste-Techniques.md).

## Entering Batch Mode Explicitly

The Batch Clipboard menu has a **Start Batch** menu item. Using this will
start batch mode with the active batch empty. The menu bar will include
"0" (zero) beside the menu bar icon.

You may wish to often or always use Batch Clipboard by starting an empty batch
and then copying with your frontmost application's **Copy** (or **Cut**)
commands instead of using the keyboard shortcut
<kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>.
If this is the case, you can choose to add a keyboard shortcut for
**Start Batch** in the Batch Clipboard Settings window.

For example you could delete this default shortcut for **Copy into Batch**
and instead make <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>
the shortcut for **Start Batch**. Or choose something different and sometimes
use that and sometimes use the default **Copy into Batch** shortcut, or change
them both 🤷‍♂️.

See also [Menu Items](Menu-Items.md) and [Settings: General](General-Panel.md).

## Beyond the Keyboard Shortcuts

A secret ways to enter _batch mode_ besides the keyboard shortcuts and menu
items is to click the Batch Clipboard menu bar icon with <kbd>CONTROL (^)</kbd>
pressed (the menu doesn't open).

When you're already in _batch mode_, doing the same again is a shortcut for
**Cancel Batch**. So holding <kbd>CONTROL (^)</kbd> when clicking the
Batch Clipboard menu bar icon, in effect, toggles in and out of _batch mode_.

See also [Special Menu Icon Actions](Special-Menu-Icon-Actions.md).

## Using Clipboard History

Documentation of the history features are coming soon.
