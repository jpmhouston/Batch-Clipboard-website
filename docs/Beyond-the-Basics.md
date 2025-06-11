## About Batch Mode

When using the Batch Clipboard keyboard shortcut
<kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>
the clipboard enters a new _batch mode_ where items you copy get stored,
and using <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd>
will paste them one-at-a-time replayed in the same order.
After you paste all the items in the batch, the clipboard returns to
normal.

> _So only use Batch Clipboard's special keyboard shortcuts when you're copying
and pasting a batch of items,_ batch mode _is not meant to be left on.
If you've pasting some of the items from the batch but not all, leaving_
batch mode _still on, then the clipboard will behave somewhat unexpectedly:
if you copy something new, using **Paste** in the frontmost application will
not paste that, but instead the next item in the batch. If you haven't started
pasting items from the batch however, the clipboard will function similar to
normal although you'll see the number beside the Batch Clipboard menu steadily
increasing._

You may wish to cancel _batch mode_ if you've changed you mind about pasting
some or all of the items you copied. Cancelling is done with the **Cancel Batch**
menu item (or a quicker way, see below).

> _However, if you've found you've copied the wrong thing, you perhaps_ don't
_need to cancel and start over. It_ is _possible to delete an item from the
batch, see [Batch Mode Menu Items](https://github.com/jpmhouston/Cleepp/wiki/Batch-Mode-Menu-Items)._

Also, while in _batch mode_ and after you've started pasting from the batch,
it's fine to copy more items. Those items copied will get added to the end
of the batch, becoming the last items to paste.

## Beyond the Keyboard Shortcuts

Here are the additional ways to use _batch mode_ besides the keyboard shortcuts:

- You may click the Batch Clipboard menu bar icon with <kbd>CONTROL (^)</kbd>
pressed to enter _batch mode_ (the menu doesn't open), or click the icon
normally to open the menu and choose **Start Batch**.

- You can exit _batch mode_, discarding the set of copies made, and return to
normal clipboard behavior by again clicking the Batch Clipboard menu bar icon
with <kbd>CONTROL (^)</kbd> pressed (the menu doesn't open), or click the icon
normally to open the menu and choose **Cancel Batch**.

- Once you're already in _batch mode_, you may use the frontmost application's
normal **Copy** or **Cut** command instead of the Batch Clipboard keyboard
shortcut, they'll still be added to the batch.

    _(So Batch Clipboard's special copy keyboard shortcut, or **Copy to Batch**
menu item, is really just a convenient way to enter_ batch mode _and then
copy the first item)_

- You _do_ need to paste using the Batch Clipboard keyboard shortcut
<kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd>,
or use the **Paste from Batch & Advance** menu item, to paste from the batch
plus automatically advance to the next item. If you use **Paste** in the
frontmost application then it will paste the next item in the batch but
not advance.

    You might, however, intentionally paste using the frontmost application's
command to intentionally paste the next item in the batch multiple times,
or if you need to use a special paste command in your application
(such as **Paste and Match Style**).

    _(To do so with the first item in the batch, you need to first use the
**Start Replaying Item** to put it on the clipboard. Before then, while
just collecting items into the batch, the most recent item to be copied
is left on the clipboard)_

    To then advance manually without pasting, use the
**Advance to Next Batch Item** menu item.

See also [Special Menu Icon Actions](https://github.com/jpmhouston/Cleepp/wiki/Special-Menu-Icon-Actions) and [Menu Items](https://github.com/jpmhouston/Cleepp/wiki/Menu-Items).

## Using the Start Batch Shortcut Instead

You may wish to forego the Batch Clipboard copy keyboard shortcut
altogether and instead assign a shortcut to **Start Batch**. You may do
so in the General panel of Batch Clipboard's Settings, see [Settings](https://github.com/jpmhouston/Cleepp/wiki/Settings).

Instead of the default workflow for Batch Clipboard:

* <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>,

    <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>,
    
    ...

* <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd>,

    <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd>,
    
    ...

your workflow will be:

* _your custom keyboard shortcut for **Start Batch**,_

* **Copy** or **Cut** _using the frontmost application's commands_,

    **Copy** or **Cut**,
    
    ...

* <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd>,

    <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd>,
    
    ...

Less symmetrical and memorable, but you may prefer it.
