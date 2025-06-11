You can issue a shell command in Terminal or a script to tell Batch Clipboard
to stop monitoring the clipboard and ignore anything copied for as
long as you need:

```sh
defaults write lol.bananameter.batchclip ignoreEvents true
```

Enable monitoring again with:

```sh
defaults write lol.bananameter.batchclip ignoreEvents false
```

This is useful if you have some workflow for copying sensitive data.
You can set `ignoreEvents` to true, copy the data and set `ignoreEvents`
back to false. While Batch Clipboard is ignoring the clipboard the menu bar icon
will appear disabled.

You can do the same by clicking the Batch Clipboard menu icon with
<kbd>SHIFT (⇧)</kbd> + <kbd>CONTROL (^)</kbd> + <kbd>OPTION (⌥)</kbd>
pressed. Do this once to start ignoring the clipboard, and again to resume
monitoring it.

*Also, using **Start Collecting** or **Copy & Collect** or the
keyboard shortcut <kbd>CONTROL (^)</kbd> + <kbd>COMMAND (⌘)</kbd> + <kbd>C</kbd>
will also re-enable clipboard monitoring, because Batch Clipboard needs to
monitor in order to collect copied items.*

You can also click the menu icon with <kbd>CONTROL (^)</kbd> + <kbd>OPTION (⌥)</kbd>
pressed to ignore only the next copy. After the next copy, normal clipboard
monitoring will automatically resume and the menu bar icon will be restored
to normal.

---

Previous: [[Advanced]]\
Next: [[Ignore Custom Copy Types]]