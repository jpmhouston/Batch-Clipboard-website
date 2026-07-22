Menu itens in the application's menu are mentioned here, which means the menu
opened by clicking the Batch Clipboard icon on the right side of the menu bar,
as described in [The Basics](The-Basics.md).

The application's Settings window is mentioned here too, it's opened by the
**Settings** menu item in the Batch Clipboard menu. It contains tabs for panels
of options, such as the tabs **General**, **Keys**, and **Advanced**. For more
about this window and each of its panels, see [Settings](Settings.md).

## Easy Peasy Keyboard Shortcuts

This is the default way to use Batch Clipboard, as described in [The Basics](The-Basics.md)
(and simplified a bit more even, for brevity):

1. <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd> some number of
times to copy clips
2. <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd> equally many
times to paste them

The menu icon normally shows its unhighlight icon. While copying you'll see
the menu bar icon highlight and a counter beside it increase,
then decrease while you paste and when it decrements past 1 the menu bar icon
returns to normal.

>More about using the global keyboard shortcuts:
>
>These default keyboard shortcuts are similar to the stardard **Copy** and
**Paste** keyboard shortcuts almost all applications use, plus this specific
combination of modifier keys are rarely used with <kbd>C</kbd> and <kbd>V</kbd>
by those applications. You may find this memorable enough so that you'll actually
use Batch Clipboard when the need arises.
>
>The keyboard shortcuts can however be customized if the applications you use
assign <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd> or <kbd>V</kbd>
themselves, or if you want to pick something else that's more memorable to you,
or is easier for you to invoke on the keyboard. Do so in the Settings tab **Keys**.

## Menu Commands

If you forget the keyboard shortcuts, these copy and paste actions are also in
the Batch Clipboard menu as items:

- **Copy Into Batch**
- **Paste & Advance**

As usualy, these menu items are badged with a reminder of the keyboard shortcuts.

## With the Menu Bar Icon Hidden

You can use the keyboard shortcuts as described above, but you're able to hide the
menu bar icon when you're using the clipboard's normal behavior. Upon collecting
the first clip into a batch the icon appear, and after pasting the last in
a batch, the icon hides again.

> You may with to do this if you things are too crowded on the right side of your
menu bar, and if you've managed to remember the keyboard shortcuts (the defaults
or however you've customized them).

Turn this on using the option **Hide Menu Bar Icon When Not in Use** in the
Settings tab **General**.

>When the menu bar icon is hidden, you can temporarily reveal it again by
re-launching Batch Clipboard from the Finder or from Spotlight.

>In addition, you can turn on the option **Show application icon in the Dock**,
also in the **General** tab. Then clicking the Dock icon also reveals the menu.
Plus, being visible in the Dock causes it to be visible in the
<kbd>COMMAND (⌘)</kbd> + <kbd>Tab</kbd> application switcher too, switching to
Batch Clipboard with that also reveals the menu.

---

## And If You Want to be Tricky

The keyboard shortcut <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>
enters _batch mode_ plus does a Copy right after. You may wish to not use
that at all and instead one of these techniques to just enter _batch mode_
explicitly. Doing any of them highlights the menu bar icon with a count of 0
beside it.

As mentioned in [Beyond the Basics](Beyond-the-Basics.md), _batch mode_ is
when using Batch Clipboard to collect many clips, and also when pasting them.
When in _batch mode_ the menu bar icon highlighted with the count of items
collected and not yet pasted beside it. Then after they are all pasted the
clipboard returns to normal.

These 5 alternatives all share the same steps 2 & 3, they only differ
in step 1 for starting _batch mode_ ...

## Menu Item to Explicitly Start Batch Mode

1. Pick **Start Batch** from the Batch Clipboard menu
2. Use **Copy** in your application or <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>
some number of times to copy clips
3. <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd> equally many
times to paste them

> This workflow is not very convenient when you have the menu bar hidden using
the option in Settings mentioned above.

## Just the Menu Bar Icon to Explicitly Start Batch Mode

1. Control-click or right-click the Batch Clipboard icon in the menu bar,
2. Use **Copy** in your application or <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>
some number of times to copy clips
3. <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd> equally many
times to paste them

> This workflow is _also_ not convenient when you have the menu bar hidden using
the option in Settings mentioned above.

Also, if you're already started _batch mode_, and the icon is highlighted, a
control-click or right-click on the icon cancels _batch mode_ and returns your
clipboard behavior to normal and the icon to unhighlighted.
See [Special Menu Icon Actions](Special-Menu-Icon-Actions.md).

## Keyboard Shortcut to Explicitly Start Batch Mode

Assign a custom keyboard shortcut to **Start Batch** in the Settings tab **Keys**.
By default there is no key combination assigned. Then:

1. Your keyboard shortcut
2. Use **Copy** in your application or <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>
some number of times to copy clips
3. <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd> equally many
times to paste them

## Re-launch Batch Clipbaord to Start Batch Mode

You can re-launch Batch Clipbaord by double-clicking its icon in the Finder,
or by searching and selecting it in Spotlight. Normally this either reveals the
menu bar icon if it's hidden. But if you turn on
**Re-launching application starts batch mode** in the Settings tab **General**
then you can use this workflow:

1. Re-launch Batch Clipbaord
2. Use **Copy** in your application or <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>
some number of times to copy clips
3. <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd> equally many
times to paste them

## Dock Icon to Start Batch Mode

If you also turn both **Show application icon in the Dock** _and_
**Re-launching application starts batch mode** in the Settings tab **General**
then you can use this workflow as well:

1. Click Dock icon
2. Use **Copy** in your application or <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>
some number of times to copy clips
3. <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>V</kbd> equally many
times to paste them

---

## More Tricks

To learn other techniques for experts, see
[Advanced Copy and Paste Techniques](Advanced-Copy-and-Paste-Techniques.md).
