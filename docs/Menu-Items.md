[[https://github.com/jpmhouston/Cleepp/blob/forkmain/Designs/Cleepp/Normal%20menu.png|alt=Normal Menu]]

- **About Batch Clipboard...** will open the about box for the app with links
for opening the homepage, it’s source code on GitHub,
for sending support email, and for opening the Intro window.\
\
Holding <kbd>SHIFT (⇧)</kbd> changes this menu ite to **Show Intro...**, reopening
the window that was shown when running the app for the first time with: a walkthrough
of granting permission to Batch Clipboard in the Settings app, a brief introduction
to its features, links to more information such as these documentation pages.

- **Start Batch** to start a set of copies. It will put the clipboard into *batch mode*.\
\
Richt-clicking the menu, or clicking the menu icon with <kbd>CONTROL (^)</kbd>
pressed does the same thing when the clipboard is in normal mode, starting *batch mode*.\
\
When already in *batch mode* this menu item will be replaced by
**Start Replaying Items** which will put the first item of the batch on the clipboard
(useful if you want to paste it using your frontmost app's menu commands instead of
the Batch Clipboard shortcut).

- **Cancel Batch** to exit *batch mode* and return to normal clipboard behavior.\
\
Richt-clicking the menu, or clicking the menu icon with <kbd>CONTROL (^)</kbd>
pressed does the same thing when the clipboard is in *batch mode*, returning to normal.

- **Copy to Batch** will enter *batch mode* if it isn’t already, and tell the
frontmost application to perform a copy. The default shortcut
<kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>
can be changed in the settings, see [[Settings]].

- **Settings...** will open a settings window, see [[Settings]].
The shortcut for this menu item, <kbd>COMMAND (⌘)</kbd> + <kbd>,</kbd> is not global
and will only work when the Batch Clipboard menu is open.

- **Quit Batch Clipboard** will remove Batch Clipboard from the menu bar and
stop it from monitoring the clipboard.
The shortcut for this menu item, <kbd>COMMAND (⌘)</kbd> + <kbd>Q</kbd> is not global
and will only work when the Batch Clipboard menu is open.

—

Previous: [[Special Menu Icon Actions]]\
Next: [[Batch Mode Menu Items]]