# sublime-preferences
Don't ever lose your subl prefs again

1. close sublime
1. clone the repo
1. run these bash commands in terminal

```bash
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/

# out with the old
rm -f Default\ \(OSX\).sublime-keymap Package\ Control.sublime-settings Preferences.sublime-settings

# in with the new
cp ~/code/sublime-preferences/Default\ \(OSX\).sublime-keymap Default\ \(OSX\).sublime-keymap
cp ~/code/sublime-preferences/Package\ Control.sublime-settings Package\ Control.sublime-settings
cp ~/code/sublime-preferences/Preferences.sublime-settings Preferences.sublime-settings
```