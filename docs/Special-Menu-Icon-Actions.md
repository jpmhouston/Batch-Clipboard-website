There are some actions that can be be triggered just by clicking the menu bar icon.
Clicking with these modifiers pressed will have the effects described below
(the menu won’t open):

- With <kbd>CONTROL (^)</kbd> pressed, or right-click: start *batch mode*.

    If currently collecting or replaying menu items then this will instead cancel
*batch mode* and return the clipboard to its normal behaviour.
See also **Start Collecting** in [Menu Items](Menu-Items.md).

- With <kbd>CONTROL (^)</kbd> + <kbd>OPTION (⌥)</kbd> pressed:
have Batch Clipboard ignore the next item copied to the clipboard.

    You may want to do this if you’re dealing with sensitive data and prefer no
record of it be saved. See also [Turn Off Clipboard Monitoring](Turn-Off-Clipboard-Monitoring.md).

- With <kbd>SHIFT (⇧)</kbd> + <kbd>CONTROL (^)</kbd> + <kbd>OPTION (⌥)</kbd> pressed:
have Batch Clipboard begin ignoring all items copied to the clipboard.

    Click with (all) those modifiers held down again to resume monitoring the clipboard,
or enter *batch mode* (by clicking the menubar with <kbd>CONTROL (^)</kbd> held,
or using the menu item, or the Batch Clipboard copy keyboard shortcut).
The menu bar icon will appear disabled for the duration while the clipboard is being
ignored.

> _By default, Batch Clipboard's history features are off as macOS now ships
with a similar feature. When history features are off Batch Clipboard only
monitors the clipboard when _batch mode_ is on, indicated by the number
beside its menu bar icon. At all other times Batch Clipboard is not doing
anything in the background, not monitoring the clipboard, not storing any new
data.

Also, clicking the clicking the menu bar icon with <kbd>OPTION (⌥)</kbd> pressed
will opens the expanded Batch Clipboard menu, which also includes recent history of
everything on the clipboard. This gives you some features for replaying past items
from the recent clipboard history.

See [Expanded Menu](Expanded-Menu.md) and
[Start Batch Mode From History](Start-Batch-Mode-From-History.md).

In short:

- <kbd>CONTROL (^)</kbd> pressed: toggle *batch mode*
- <kbd>OPTION (⌥)</kbd> pressed: show the expanded menu if history features are on
- <kbd>CONTROL (^)</kbd> + <kbd>OPTION (⌥)</kbd> pressed: privacy
