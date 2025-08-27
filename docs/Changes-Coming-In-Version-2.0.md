Version 2.0 of Batch Clipboard in nearly ready. It's a substantial update with a lot of changes, both visible and under the hood.  
Here's the TL;DR:

1. A simpler and more efficient history-off mode is now the default.
2. A repeat last batch feature, paste the same set of clips again without going back to re-copy them.
3. In the app store version after in-app purchase: saved batches to repeat anytime later.

You may download beta versions from GitHub [here](https://github.com/jpmhouston/Batch-Clipboard/), or join TestFlight as a tester of the App Store version [here](https://testflight.apple.com/join/epg3cusH).

Below is the full list of changes taken from the project's [changelog](https://github.com/jpmhouston/Batch-Clipboard/blob/main/CHANGELOG.md). If there are any more changes of note before the final release then they'll be added here.

### New in beta 2, 2025-08-22:

- Added support for a beta channel to Sparkle updates in the non-app store version, a checkbox in the General panel of the Settings window to get betas in addition to final releases, a new menu item just below About... when an update found. If the user cancels the update alert on launch then they can use this menu item instead of going into the Settings window.
- Revise the menu items some more, tweaking the titles of several items, changing which are shown and disabled when not applicable vs hidden.
- New extra feature for the app store releases, checkbox in the Advanced panel of the Settings window to hide the menu bar icon when the app has no active batch, or when the application re-opened in the Finder (also causes the Settings window to open).
- Fixes and improvements to the application intents accessible from Shortcuts and Spotlight.

### Earlier changes

- Implemented major feature: ability to turn history off for simplicity and system effeciency, now the default.
- When history off and without need to stay consistent with its bottom-up order, ie. most recent at the top, the current batch is now shown in top-down order, ie. first to paste at the top.
- Migrating from 1.0.x to 2.0 shows a Intro page offering to switch to the new history-off default or keep using history, the default for those users is to keep using the history features unless they choose to switch then or later in the Settings window Storage panel.
- Implemented major feature: replaying previous batch again, and support giving the menu item a keyboard shortcut (empty by default).
- Implemented major feature for app store version users who've made an in-app purchase: saving current or previous batches, each can have an optional keyboard shortcut. They appear in a new section of the menu when there's no current batch active, each with their clips in a submenu and items to replay, rename. A saved batch or individual clips within can be deleted with the same command-delete shortcut when the menu is open.
- Improved feature for app store version users who've made an in-app purchase: in-between pasting multiple clips at a time from the current batch, a new option to insert a space, newline, or comma.
- By necessity, the Undo Last Paste feature for app store version users who've made an in-app purchase is now removed in the new default history-off mode.
- Menu simplification: in new default history-off mode, no complication of a different form of the menu when its opened with the option key pressed.
- Menu simplification: the Start Replaying and Advance menu items are now hidden by default. They can be restore with an option in the Settings window Advanced panel.
- Menu simplification: the type-in filter history field, the one that's available in the expanded menu when history on for app store version users who've made an in-app purchase, this is hidden by default unless turned on in the Settings window Appearance panel.
- Minor improvements to the menu: when deleting items from the menu with command-delete the menu no longer closes, new title labels over Current Batch, Saved History, Saved Batch sections.
- Improved simplicity of how the menu is opened in reaction to clicks in hopes of addressing possible failures, stripping some unused feature of the old behavior inherited from Maccy. Added an option to the Settings window Advanced panel for reverting to the old behavior in case of incompatibilities.
- Improved layout and location of options in Settings window panels: new history switch and related menu size fields together in the Storage panel, new or improved descriptive labels in the General, Appearance, and Advanced panels.
- Improved layout and language in the Intro window, including descriptions of IAP-unlocked features in the app store version.
- Unit tests to verify correct queue, history behavior, and also general backing store correctness including migration from older versions. Improved menu reliability with sanity checking and logging of unexpected conditions.
- Migrated source to new GitHub repository that isn't a fork of Maccy.

Known issues:
- An icon for macOS 26 Tahoe is coming.
- GitHub vesions already inform you of updates and allow you to easily download and install them, but it soon let you choose to follow beta releases as well.
