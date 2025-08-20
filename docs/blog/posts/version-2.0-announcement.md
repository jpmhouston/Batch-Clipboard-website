---
date: 2025-08-18 
categories:
  - Notice
  - Updates
  - Features
---

# An Announcement About Batch Clipboard Version 2.0!

As described last month in a [teaser blog post](https://batchclipboard.bananameter.lol/blog/2025/07/25/batchclipboard-1.1-coming-soon/), a new and improved version of the Batch Clipboard app for macOS is in beta and imminently will be available to testers in TestFlight. The changes we've been able to finish turned out to be substantial enough to warrant the version number 2.0 instead of just 1.1.

To not bury the lede, in celebration of the first beta of this new version, the in-app purchase in the Mac App Store's current version, 1.0.3, will be half price for the next 4 weeks, or as long as it takes for 2.0 to go final. For that time it's a one-time purchase of now US$1.99 that never expires, so will count for version 2.0. Read on to hear what it unlocks.

---

First however, what is Batch Clipboard? It's a minimal clipboard utility for the Mac that strives to be far simpler than a full clipboard manager and provides mostly just the one feature other apps describe as serial paste, or a clipboard queue. Its user experience is just a top-right menu and global keyboard shortcuts: the same Command-C and Command-V you know but with Control also held down, so <kbd>^⌘C</kbd> and <kbd>^⌘V</kbd>.

It has no large window demanding you to now "manage" your clipboard history. However, somewhat hypocritically, it has stealthily provided a clipboard history feature visible by opening its menu with the option key pressed. During the lead up to 1.0 as well, some features were added for completeness but sacrificing more of the app's intended simplicity.

---

Version 2 is all about regaining simplicity yet extending the batch feature in a new and terrifically useful direction:

1. Now, by default, the app no longer collects your clipboard history! With macOS 26 getting this as a built-in feature, this was an easy decision with some interesting implications...
   
    Firstly, this permitted the change to arrange the menu items representing the current batch in a more natural top-down order, the one first in the menu being the one that will be pasted first.
    
    Secondly, by foregoing history, the app is largely able to turn off its background clipboard monitoring. Only after invoking the start of a batch, or the first batch copy with the menu or shortcut, does the app start monitoring the clippboard in the background.

    Finally, for the set of existing users, we didn't want to yank features away so we decided to continue supporting the history feature if the user chooses that. This lets the user continue to open the menu with the option key pressed to view and choose history items to repaste, and user of the App Store version who've made the in-app purchase can continue replay a batch of clips from the reent history and use the Undo Last Copy menu item.

2. A new feature that recalls the previous batch pasted, so the whole set can be pasted again.

    This improves upon a feature that was previously only available in the App Store version after making an in-app purchase. This non-free feature was cumbersome, yet this new feature that replaces it is available to all and far more straight-forward, just a simple new menu item.
    
    Also, the General panel in the Setting window allows you to pick a custom keyboard shortcut to invoke it. Take that, version 1.0!
  
3. A winning expansion on this feature for users making an in-app purchase in the App Store version: **saved batches**.

    The most recent batch copied, in addition to being replayed again, can be saved along with a title, and it will be shown and selectable in the menu anytime.
    
    Each saved batch can also be given its own custom keyboard shortcut. 🤯

A more complete list of changes since version 1.0.3 is available [here](https://batchclipboard.bananameter.lol/Changes-Coming-In-Version-2.0).

---

The 2.0 version will be available from the Mac App Store at [https://apps.apple.com/app/batch-clipboard/id6695729238](https://apps.apple.com/app/batch-clipboard/id6695729238), or from GitHub at the new link [https://github.com/jpmhouston/Batch-Clipboard/releases](https://github.com/jpmhouston/Batch-Clipboard/releases), and also I expect the GitHub releases to be available from homebrew with `brew install batchclipboard`.

Beta versions will be available before then on GitHub, and you're also welcome to sign up to test betas of the App Store version via TestFlight at [this link](https://testflight.apple.com/join/epg3cusH). But note, in-app purchases made in a TestFlight beta aren't real, you aren't charged and they won't count for the final release. If you want to test the beta in addition to taking advantage of the half price in-app purchases price, then:

- First get the current release version from [here on the Mac App Store](https://apps.apple.com/app/batch-clipboard/id6695729238),
- Visit the Setting window's Support Us panel and complete the purchase,
- Find Batch Clipboard in your Applications folder and trash it,
- Finally visit [this TestFlight page](https://testflight.apple.com/join/epg3cusH) and follow the instructions to become a tester and download the beta.
