---
date: 2025-12-07
categories:
  - Notice
  - Updates
---

# An Important Bug-fix Update to Batch Clipboard 2

Version 2.0 of Batch Clipboard was released this fall to acclaim and well-regard.
Alas, some bugs crept into that version which have finally been fixed.
To every user of the app we extend our sincerest apologies for not catching these issues earlier,
and also heartfelt thanks to the testers who helped reveal and fix them.

Also, a thank you to the developers of each open source library the app leverages to implement its features,
specifically those with recent updates that have been included in this version.

Users of the App Store edition should soon be offered an upgrade to this version automatically.
Users of the non-App Store edition who have "Check for updates automatically" turned on
in the settings will also be offered an automatic upgrade soon.
For non-App Store users without automatic update checking turned on, choose the "Settings"
item at the bottom of the Batch Clipboard menu, and in the window that opens, use the "Check Now" button. 

-----

Changes in version 2.2:

- Fixed a crash that was occurring after copying text that contains non-breaking space and potentially other special characters.
- Fixed a crash that was occurring when using Undo Last Copy, a feature unlocked by In-App Purchase in the App Store version.
- Corrected the set of batch menu items visible in the menu after some are pasted, including the badge that indicates the next one to be copied.
- Tahoe UI update in the Settings window (from upgrading the Settings library dependency).
- UI updates in auto-update dialog for non-App Store build (from upgrading the Sparkle library dependency).
- Potential minor fixes to purchasing in App Store build (from upgrading the Flame library dependency).
- Corrected the source-code project setup that claimed to have localizations that were missing, possibly having a minor impact on non-English systems to avoid presenting the app as localized when it isn't.

_Regarding that last change, feedback is always welcome regarding the use of the app on non-English systems.
With more support, development of the app can continue with the aim of localizing it into multiple languages.
Please consider the in-app purchase within the Settings window of the App Store version,
and/or donate to the app at [buymeacoffee.com](https://www.buymeacoffee.com/bananameterlabs)._

-----

Batch Clipboard is avaiable in the Mac App Store [here](https://apps.apple.com/app/batch-clipboard/id6695729238)
and if you prefer to manually install the non-App Store edition then it's available [on GitHub](https://github.com/jpmhouston/Batch-Clipboard/releases/latest).
Please also consider adding a star on the GitHub repository to permit us adding the application
as a homebrew cask, and let nerdy users choose to easily install from their terminal command-line.

See also the app's information and documentation site at [batchclipboard.bananameter.lol](https://batchclipboard.bananameter.lol).
