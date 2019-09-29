REG - Syntax Package for Sublime Text 2/3
============

Windows Registry Script (.reg) Language package for SublimeText. Includes syntax highlighting, comments toggling, declaration snippets, a build system to merge current reg file to registry, and a `Jump To Reg Key` command.

The `Jump To Reg Key` command will use the key name enclosed in square brackets at the location of your keyboard caret and jump to it in your registry editor.

By default this is done using Windows Registry Editor (aka regedit). You can specify to use a different registry editor by selecting the menu item `Preferences > Package Settings > REG > REG Settings - User` and modifying the `reg_editor` entry, and setting `use_regedit` to `false`.

Settings specified in REG.sublime-settings in your User folder are retained even when the package is updated.


## Installation

### By Package Control

1. Download & Install `Sublime Text 3` (https://www.sublimetext.com/3)
1. Go to the menu `Tools -> Install Package Control`, then,
   wait few seconds until the `Package Control` installation finishes
1. Go to the menu `Preferences -> Package Control`
1. Type `Package Control Add Channel` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Now, go again to the menu `Preferences -> Package Control`
1. This time type `Package Control Install Package` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, search for `REG` and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.

