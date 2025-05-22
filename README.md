# mc3ds-mods
Collection of mods for Minecraft: New Nintendo 3DS edition that I have made.

Each folder contains the romfs directory for the game, simply copy the romfs for whatever mod you want into your game's mod folder and boot the game.
# About my mods
Not all of these mods can be merged together! Some will overwrite the same files or break functionality with eachover. Please be careful when merging mods and if something breaks remove your romfs folder!

# Thanks to the MC3ds modding community including my good friends; Cracko, wyndchyme, Vance, STB and PizzaLeader.


# Optimized Table zip
This zip is designed to act as a library/ modding base which optimizes loot table jsons in the latest update to free up more json files for custom stuff. You are encouraged to use it as a base for making your own mods.

LIST OF UNUSED JSONS IN 1.9 ROMFS FOR MINECRAFT 3DS EDITION
server > entities:
-agent
-husk
-mushroom_cow
-npc
-wither_boss
-bat
LIST OF MOBS WITH LOOT TABLES THAT CAN BE REPLACED WITH EXISTING ONES
server> loot_tables > entities:
-mooshroom (change to use cow.json)
-zombie horse (change to use zombie.json)
-llama (change to use horse.json)
-cave_spider (change to use spider.json)
-wolf (remove loottable component)
-silverfish (remove loottable component)
-ocelot (remove loottable component)
-boat (remove loottable component)
NOTE: the attached zip folder contains edited entity jsons which optimize the loottable usage to free up the above mob loot jsons 
