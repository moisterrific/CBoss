# CBoss

A simple way to spawn npcs with modifiable health values. Able to be used from the console. I originally designed this to be used with SmartRegions as the /spawnmob command gave me a "This command must be used in game" error when I tried to spawn a mob by entering a SmartRegion.

Commands:

/cboss <npc ID> <region name> - Spawns an npc near the center of the given region.
/cboss <npc ID> <region name> <count> - Spawns <count> number of npcs near center of the given region.
/cboss <npc ID> <region name> <count> <health> - Spawns <count> number of npcs near the center of the given region with <health> amount of health.

Example:

/cboss 262 arena 14 500000

This command would spawn 14x Plantera with 500,000 health each near the center of region "arena". Be careful when using a modified health. Mobs have a max number of allowed health and going over this limit will produce unexpected results.

Things to note:

Spawning npcs with a max amount of health higher than the game permits will produce unexpected results.
Spawning npcs with segments such as The Destroyer more than 2 times will produce unexpected results (I.E. the third boss will not have all of its segments).

To-Do:

Figure out how to change the displayed maximum health on the npc spawned.
Create a list of maximum health for commonly spawned npcs. 

[CBoss](https://tshock.co/xf/index.php?resources/cboss.168/)
