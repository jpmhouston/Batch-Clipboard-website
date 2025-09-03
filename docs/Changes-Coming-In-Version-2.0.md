# Changes in Version 2.0

Version 2.0 of Batch Clipboard is now available (or will be soon) from [GitHub](https://github.com/jpmhouston/Batch-Clipboard/releases/latest) or the [Mac App Store](https://apps.apple.com/app/batch-clipboard/id6695729238). It's a substantial update with a lot of changes, both visible and under the hood.

TL;DR:

1. new Repeat Last Batch menu item
2. setting to hide the menubar icon
3. performance and simplification improvements
4. for app store in-app purchasers: save batches to repeat anytime later

Below is the list of the 20 main changes and improvements summarized from the project's full [changelog](https://github.com/jpmhouston/Batch-Clipboard/blob/main/CHANGELOG.md).

> The remaining documentation pages [starting here](Installing-and-Starting.md) are written for version 1.0, but will be updated shortly.

- Feature: the ability to turn history off for simplicity and system efficiency with option in the Settings window Storage panel, with the default for new users being off.
- Feature: users migrating from 1.0.x to 2.0 shows an Introduction window page offering to switch to the new history-off default or keep using history.
- Feature: retaining the most recent batch in the application's database so it can be replaying again from a menu item, and support giving it a keyboard shortcut (empty by default).
- Feature: saving the current or previous batch indefinitely, each saved batch recalled from menu items a new section of the menu, each can have an optional keyboard shortcut.
- Feature: enhancement to Paste Multiple, in-between pasting each clip a new option to insert a space, newline, or comma.
- Feature: the ability to hide the menu bar icon when the app has no active batch, or after re-opening the application from the Finder, controlled by an option in the General panel of the Settings window.
- Improvement: the current batch being copied or pasted is now shown in the menu in top-down order, first to paste at the top.
- Improvement: when deleting items from the menu with command-delete the menu no longer closes.
- Improvement: for clarity, new title labels over Current Batch, Saved History, Saved Batch sections.
- Improvement: revised some menu item titles, order, and made more shown and disabled when not applicable instead of hidden for consistency and discoverability.
- Improvement: better layout and location of options in Settings window panels, with new history switch and related menu size fields together in the Storage panel, new or improved descriptive labels in the General, Appearance, and Advanced panels.
- Improvement: better layout and language in the Introduction window, descriptions of IAP-unlocked features in the app store version, its window title.
- Improvement: for simplification, the Start Replaying and Advance menu items are now hidden by default, controlled by an option in the Settings window Advanced panel.
- Improvement: for simplification, the type-in filter history field is hidden by default, controlled by an option in the Settings window Appearance panel.
- Improvement: the Undo Last Paste feature that requires clipboard history now hidden for simplicity when history features disabled.
- Improvement: simplified internal mechanism inherited from Maccy for how the menu is opened, with option to revert in the Settings window Advanced panel in case of incompatibilities.
- Improvement: support for a beta channel for updates to the non-app store version, with a checkbox in the General panel of the Settings window to include beta updates.
- Improvement: when update available in the non-app store version, a persistent menu items added in case the user closes the update notification window.
- Improvement: fixes and additions to the application intents accessible from Shortcuts and Spotlight.
- Improvement: migrated source to a new GitHub repository that isn't a fork of Maccy, now registration to download and install by name using homebrew is possible (ie. without an intermediate tap).
