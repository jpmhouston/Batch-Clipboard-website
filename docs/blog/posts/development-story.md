---
date: 2025-05-16 
categories:
  - Information
---

_Here's a little explanation of how this app came to be, originally written in response to a question on reddit._

---

At work a few years ago I found myself having to copy many items text from one app to another with regularity. Having to do copy swap, paste swap, (repeat many times) made me start looking for a solution that let me copy all them, swap once, paste all of them. I saw many clipboard managers that added fancy UI for browsing through clipboard history and other features, but I don’t remember seeing one solving this specific issue. I put writing this myself on my mental todo list.

Initially I wanted not to need a global paste hotkey and started experimenting with promised pasteboard items. If turned on, my hypothetical app polling the clipboard would transform an item just copied into a promise for that item and queue it, hoping the promise being called in would be a reliable indicator that the user had performed a paste and then swap to the next in the queue. However that wasn’t reliable, so many other apps also examined the full clipboard independent of the user's actions.

So I put the plan on the back burner, occasionally surveying open source clipboard managers I could potentially experiment with, being occasionally reminded whenever copying more than one thing from window A to window B. At one point I came to look at [Maccy](https://maccy.app).

---

Being MIT licensed I started thinking about forking Maccy and adding the feature I wanted, but I very much hoped to not step on the toes of the original. Thinking ahout my dissatisfaction with the overwhelming added user experience of clipboard managers I'd tried, I decided that my fork should not be one of these full-featured apps, but should strip out most features and primarily deliver just the feature I wanted. I experiemented in early 2024, came back to it and released betas in mid-2024 under the codename Cleepp, used the app as a reason to relearn App Store releasing and in-app purchase, and learn GitHub action workflows in late 2024, and finally get around to releasing to the Mac App Store in Spring 2025 renamed as Batch Clipboard.

---

I remimplemnted a lot regarding the Maccy's menu and while I use some of the inherited mechanism to capture and show the queued clipboard items, I considered removing all-the-time capture and display of the overall clipboard history altogether. While I didn't strip it out completely, I hide it unless the user opens the menu with the option key held. This little bit of feature creep allows a specific feature I found that I wanted: deciding after the fact to make a queue of items to paste (which I now call a batch) after the fact out of the recent items copied. This also allows replaying the same batch multiple times which I haven't come to need myself but I thought some users might.
