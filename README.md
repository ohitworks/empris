# empris readme

![](https://i.imgur.com/FcNGZjG.jpg)

It uses playerctl to get a list of players.

The labels are displayed to pick a player.

When a player is selected it triggers play-pause.

It auto-pauses all other playing players.

The menu has options for Pause All, Next, and Prev.

There's also a daemon to autopause on player switch.

Arguments passed can be "pauseall", "next", "prev", or "autopause".

No arguments show the menu.

----

Forked from [madprops/empris](https://github.com/madprops/empris/tree/main). Add sound playback device selection function by using`wpctl` .