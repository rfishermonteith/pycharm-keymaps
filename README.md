This repo stores my keymaps for PyCharm, to be shared across
computers.

The xml file (`X custom.xml`) needs to be placed where PyCharm can find it.
You can find this [here](https://www.jetbrains.com/help/pycharm/configuring-keyboard-and-mouse-shortcuts.html#custom_keymap_location)

On mac this is 
```commandline
~/Library/Application Support/JetBrains/<product><version>/keymaps
```

I've symlinked this to this repo, using 
```commandline
ln -s ~/Documents/repos/pycharm-keymaps ~/Library/Application\ Support/JetBrains/PyCharm2024.3/keymaps/keymaps
```

I haven't yet tested how this works when updating the PyCharm version.