In-Game Wiki Mod
=======

The In-Game Wiki Mod was a ModJam 3 mod originally developed by MineMararten. However, it seems maintenance for this mod was discontinued. I personal pushed a 1.11 version, but the autor never merged the mod, so it is possible that they have stopped modding. However because of the license, I am able to free update and distribute this mod as long as I provide the same license as the original.


This mod adds a Graphical User Interface (GUI) into the game. You can open this with the 'i' key (by default).

If you're hovering over a block in the world when you press the 'i' key you'll automatically be navigated to the page about this block. Likewise for entities.

The info on the pages is retrieved from text files stored in /assets/igwmod/wiki/<language>/. For blocks/items the file the mod searches for is named the same as the unlocalized name of the block/item, with either block/ or item/ prefixed. The currently included files about Vanilla are there as a proof of concept. However, if you install PneumaticCraft, you'll see a full implementation of IGW-Mod.

The info in the files can be plain text. However, there are some commands with which you can easily include crafting/furnace and even custom recipes, pictures and/or references to other block's/item's pages. A tutorial for this can be found in the mod itself. Make sure to enable 'debug mode' in the mod's config.

=======
Developping with In-Game Wiki Mod
=======
At this time this mod no longer has a maven, but if you want to develop for with IGW, the sources will be included in each release and the project is open source.

=======
Contributing to In-Game Wiki Mod
=======
If you're planning to contribute to the In-Game Wiki mods source, the best thing you can do is clone this github repository, and run 'gradle setupDecompWorkspace idea/eclipse' on the build.gradle file in this repository.

After you've made changes, do a pull request :)
