## Using The Application's _Cut_ or Special _Copy_ Command

A secret of Batch Clipboard is that when it's in _batch mode_, any changes
to the clipboard whether it's from using the global shortcut
<kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd> or using
any command in the frontmost application such as **Cut**, it will be added
to the batch.

> This is as long as the command copies to the regular system clipboard,
> and not an alternate one. One example of an alternate clipboard is the
> Ruler clipboard usually used by a **Copy Ruler** command.

If everything you want to include in the batch is by cutting rather than
copying, or at least the first item is, then the trick is to manually
enter _batch mode_ using **Start Batch** in the Batch Clipboard menu.

So to be clear, to **Cut** from the frontmost application into a batch:

1. If not yet in _batch mode_, pick **Start Batch** from the
Batch Clipboard menu. If already in _batch mode_ with a number beside
its icon in the menu bar, then step 1 is not needed.

2. Use your frontmost application's **Cut** command. The number beside
the Batch Clipboard icon in the menu bar should increment. You can also
click the icon to see what you've just cut within the menu.

> As mentioned [here](Beyond-the-Basics.md#Behind-The-Curtain),
> Batch Clipboard's global shortcut is only needed to start a batch and do
> the first copy, after which the frontmost application's copy / cut
> command or shortcut are _also_ added to the batch.
> When _batch mode_ is already started, the Batch Clipboard copy shortcut
> <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd> isn't
> really needed, it does the same as the frontmost application's **Copy**,
> but using it anyway has a memorable symmetry with the paste shortcut.

> In truth, pasting isn't really symmetrical to copying, because while a
> copy in one application _can_ be detected from another, a paste _cannot_.
> Those who don't care about presenting a fake symmetry but rather about
> exposing how things work under the hood (those who prefer cars with
> manual transmissions, say) can assign a keyboard shortcut to
> **Start Batch** in the Gerenal panel of the Setting window. See
> [Beyond the Basics](Beyond-the-Basics.md) and
[Settings - General](General-Panel.md).

## Using The Application's Special _Paste_ Command

If you frequently need to paste certain items from a batch using the
frontmost application's paste command, such as **Paste and Match Style**,
then the answer is to turn on **Show advanced paste menu items** in
the Advanced panel of the Settings window.

Turning this checkbox on reveals the additional menu items
**Start Pasting From Batch** and **Advance To Next Batch Item**.
See also [Settings - Advnaced](Advnaced-Panel.md).

Like when copying using the frontmost application's copy command, there's
a special case for the first item in a batch. For example, to use the
frontmost application's **Paste and Match Style** command for an item
from the active batch:

1. If you haven't started pasting any items from the batch yet and the
**Start Pasting From Batch** menu item in the Batch Clipboard menu is
enabled, first select that menu item. If this isn't the first item to be
pasted from the batch and this menu item is not enabled, then step 1 is
not needed.

2. Use the frontmost application's **Paste and Match Style** command.

3. Select the **Advance To Next Batch Item** menu item in the
Batch Clipboard menu.

These three steos is what **Paste From Batch & Advance** does
automatically, except invoking the frontmost application's normal paste
command. These extra menu items enabled by the option in the Settings
just allows you to manually do these individual steps.
