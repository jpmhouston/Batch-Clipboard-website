---
date: 2026-07-22
categories:
  - Notice
  - Updates
---

# A Useful Update to Batch Clipboard 2

After some lengthy consideration of what was still missing in
[Batch Clipboard](https://batchclipboard.bananameter.lol) for macOS by
[Bananameter Labs](https://batchclipboard.bananameter.lol),
version 2.3 of the application was released this week
[on the Mac App Store](https://apps.apple.com/app/batch-clipboard/id6695729238) and
[on GitHub for manual install](https://github.com/jpmhouston/Batch-Clipboard/releases/latest).
It fixes a few issues and rounds out the feature set with some things requested by users
and still others long on the back burner.

The next release planned is one that adds no new features, but does add localization
to some languages other than US English. Which languages are coming first
and the timeline of this release are still to be determined. Stay tuned!

> Along with this release is a revision to the
[documentation pages](https://batchclipboard.bananameter.lol/documentation),
importantly adding a new page which
[summarizes](https://batchclipboard.bananameter.lol/Ways-to-Use.md)
the different techniques for using with the app. It collects some details that were
strewn about other documetation pages, or previously missing, or new to this version.
There is more to do still though, including updating the now slightly out-of-date
screenshots of menus, and of Settings window panels, and also completing the details
about those panels. These updates will be rolled out in stages without fanfare,
and for this as well no timeline is set.

Thank you to the beta testers, and to friends and family. This release was completed
while the 2026 World Cup of football was ongoing, and also while our technical lead at
Bananameter Labs was away house-sitting at two different households and wrangling a
total of 5 cats between them. _Names and photos withheld but to humans K, J, A, M, T,
and critters N, D, C, L, J, thanks it was fun!_

Users of the App Store edition should soon be offered an upgrade to this version automatically.
Users of the non-App Store edition who have "Check for updates automatically" turned on
in the settings will also be offered an automatic upgrade soon.
For non-App Store users without automatic update checking turned on, choose the "Settings"
item at the bottom of the Batch Clipboard menu, and in the window that opens, use the "Check Now" button. 

-----

The new feature in version 2.3:

- Hold option key with the menu open to show Start Batch with
Clipboard, use if you cut/copy something then realize you in fact want a
batch of several clips, it starts a batch with the first item being
what’s already on the clipboard.
- New option useful when the menu bar icon is hidden: show the app in
the Dock and app switcher, and made switching to the app reveal the menu
bar icon. Added contextual menu to the Dock icon.
- Changes in the General Settings tab: made more explicit the option
for hiding the menu bar icon, added the option to turn on the Dock icon,
another to start batch mode when the Dock item clicked, moved keyboard
shortcut fields to its own new tab.
- Change in the Advanced Settings tab: one to reset previously
supressed alerts (ones containing “Don’t ask again” checkboxes), another
to enable some debug logging.
- Simplified menu when advanced paste items are enabled using the
checkbox in the Advanced tab of the Settings window. “Skip to Next” and
“Start Pasting From Batch” are now one context sensitive menu item.
- About Batch Clipboard now opens a new first About panel in the
Settings window, with more room to describe what the app does and use
real buttons for linking to further resources instead of underlined
text.
- Improved layout of the Intro window in preparation for localization,
and updated some of the content to fixing typos and improve
clarity.
- New Intro window page asking user to choose to add Batch Clipboard
as a login item. Includes an option to defer decision and show a
reminder alert after copying &amp; pasting a batch a few times.
- For IAP-unlocked saved batch feature in the App Store version: a new
Repeating setting for saved batches, made visible if new checkbox turned
on in the Advanced Settings tab. After pasting last begin pasting from
the first again, until batch cancelled.
- Also for saved batch feature: holding option key when saved batch
menu showing changes “Reply” menu item to “Replay Repeating”. Menu item
to open dialog for editing or deleting saved batches changed from
“Rename” to “Edit”, and fixes to behavior of that dialog.

And the fixes:

- Fixed alerts sometimes opening behind other applications’ windows,
and improved reliability of returning the user’s application and window
to be frontmost after using Batch Clipboard menu items or Settings
window.
- Log exceptions in release builds instead of crashing. Further
diagnosis of the few apparent edge cases that were tripping exceptions
will be done in debug builds, perhaps future betas that use an analytics
framework.
- Removed internal hidden menu bar definition that was intended to
assist localization, but added complexity and seems to have been
contributing to menu lag on some systems.
- Fixed some bugs when clipboard history is enabled.
- Fixed some warnings that were being logged to the system
console.
- Removed dependency on the package SDWebImage, not used since early
betas of version 1.

-----

Batch Clipboard is avaiable in the Mac App Store at
[https://apps.apple.com/app/batch-clipboard/id6695729238](https://apps.apple.com/app/batch-clipboard/id6695729238)
and if you prefer to manually install the non-App Store edition then it's available on GitHub at
[https://github.com/jpmhouston/Batch-Clipboard/releases/latest](https://github.com/jpmhouston/Batch-Clipboard/releases/latest).
(And if you go there, also consider adding a **star** on the GitHub repository; this will
allow us to add the application to the default homebrew index and let nerdy users
more easily discover and install it from their terminal command-line).

See also the app's information and documentation site at [batchclipboard.bananameter.lol](https://batchclipboard.bananameter.lol).
