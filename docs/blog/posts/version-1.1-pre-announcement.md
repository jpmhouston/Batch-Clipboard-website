---
date: 2025-07-25 
categories:
  - Notice
  - Updates
  - Features
slug: batchclipboard-1.1-coming-soon
---

# An Update About the Upcoming Version 1.1

An update to Batch Clipboard is in progress! It will soon be simpler, be even less of a clipboard manager, and better fit with the upcoming macOS 26 Tahoe.

The global shortcut keys Control-Command-C and Control-Command-V (or whatever you customize them to be) aren’t going anywhere, nor is their ability to collect multiple clipboard items at once and paste them where you like. However, the app is being simplified even further, eliminating a small but persistent performance hit to your system, while introducing a new, more unique feature for power users in place of the version 1.0's somewhat-hidden clipboard history features.

The new release will either be version 1.1 or 2.0, or perhaps 2.6 as a nod to Apple’s macOS 26.

-----

Previously, the app continuously monitored clipboard changes whenever it was running, maintaining a recent history whether you used that feature or not. This behavior was inherited from Maccy, the open-source project from which Batch Clipboard was forked. The batch feature and the presentation of items in the menu were built on top of that foundation. It made sense to leave clipboard history as a secondary feature, and add related bonus abilities as a perk for in-app purchasers.

Now that macOS includes a built-in clipboard history, it makes less sense to duplicate that functionality. By abandoning constant monitoring for clipboard changes, we avoid the minor performance penalty it caused. Removing clipboard history also allows us to simplify the menu item. Current version have an expanded menu (revealed with an option-click) which was designed to display the history in menu items in reverse order, bottom oldest and newest at the top. Menu item representing the current batch used to be shown the same way in compatibility with that. Now however, there will be no expanded menu displaying history and menu items showing the current batch in progress will instead be listed in a more natural, top-down order.

For anyone who relies on the current behavior, we’ve kept it as an optional mode, controlled by a switch in the Storage panel in the app’s Settings window. After upgrading, the Intro window will appear again with a new page explaining this change and letting you choose between the new behavior or the legacy mode.

Admittedly, this new default, history-free mode removes the key perk that for those who supported the app’s development via in-app purchases, as it was closely tied to clipboard history. To make up for that, we're happy to announce that a new and very exciting bonus feature is in the works, one that's been requsted and may be a great benefit for power users. Details will be announced soon, sometime after this version's first beta release on TestFlight.

-----

Batch Clipboard will remain free to download and use its core feature, as well as the legacy clipboard history feature for anyone who wants to turn that on. Anyone supporting the project via in-app purchase will get the current and future unlocked features. The app will remain open source on GitHub with a permissive MIT license.

Stay tuned!

- The folks a Bananameter Labs
