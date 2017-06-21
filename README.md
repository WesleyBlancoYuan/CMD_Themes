# CMD Themes
This is a collection of color themes for `cmd.exe` of Microsoft Windows, inspired by [this solarized theme](https://github.com/neilpa/cmd-colors-solarized). It consists of simulations of some well-known color themes in different terminals and dev environments.

The environments/editors that serves me as example of imitation are: 
 - Ubuntu terminal (purple background + white font)
 - Turbo Pascal environment (dark blue background + yellow font)
 - Legacy computers' terminal, like those of IBM in the later 80s' of last century (black background + green font).
 
Transparency is added for aesthetic reason. I also found that it increases readability. 

Instead of importing Registry entries, I decide to show the configuration in images, because of a strange fact: **each executable/shortcut of `cmd.exe` has its own configuration, so the config can only be done at executable/shortcut level.** Change color settings in "Properties" **only affects current cmd executable/shortcut and will not affect Registry entries' value**, and edit colors in "Defaults" will change registry color tables, but these values **will never be used**. Even if we run `cmd.exe` without shortcut, the config of "Properties" of it will never be seen by other shortcuts. 
 
Experiment: you can try to: 
 1) anchor a shortcut of `cmd` to task bar;
 2) create a shortcut in desktop;
 3) type `cmd` in search bar to find the executable;
 4) find `C:\Windows\System32\cmd.exe` and run it. Their color in "Properties" can be all different, and "Defaults" color are always shared, but never used.
