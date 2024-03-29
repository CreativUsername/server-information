## Modlist

This is a list of fabric mods currently installed on the server. None of these need to be downloaded for you to join the server or for the mods to work as intended. <br>
Client support may not be completely accurate in regards to the server.

0 = unsupported/unnecessary, 1 = optional but recommended, blank = unknown

| mod | version | client | 1.20.0 support | 1.20.1 support |
| --- | --- | --- | --- | --- |
| [AntiXray](https://modrinth.com/mod/anti-xray) | 1.3.0 | 0   | ✓   | ✓   |
| [Anvil Restoration](https://modrinth.com/mod/anvil-restoration) | 2.0 | 0   | ✓   | ✓   |
| [Better Than Mending](https://modrinth.com/mod/better-than-mending) | 1.3.0 | 0   | ✓   | ✓   |
| [Bypass Anvil Restriction](https://www.curseforge.com/minecraft/mc-mods/bypass-anvil-restriction) | 1.0.4 | 1   | ✗   | ✗   |
| [Carpet](https://modrinth.com/mod/carpet) | 1.4.101 | 1   | ✓   | ✓   |
| [Carpet Extra](https://modrinth.com/mod/carpet-extra) | 1.4.100 | 0   | ✓   |     |
| [Cloth Config API](https://modrinth.com/mod/cloth-config/) | 10.0.96 | 0   | ✓   | ✓   |
| [Collective](https://modrinth.com/mod/collective) | 6.54 | 0   | ✓   | ✓   |
| [Command Aliases](https://modrinth.com/mod/commandaliases) | 1.0.1 | 0   | ✓   | ✓   |
| [Day Dream](https://modrinth.com/mod/day-dream) | 1.0.7 | 0   |     | ✓   |
| [Double Doors](https://modrinth.com/mod/double-doors) | 4.5 | 1   | ✓   | ✓   |
| [Dynmap](https://www.curseforge.com/minecraft/mc-mods/dynmapforge) | 3.5 | 0   | ✓   | ✓   |
| [Essential Commands](https://modrinth.com/mod/essential-commands) | 0.33.0 | 0   | ✓   |     |
| [Fabric API](https://modrinth.com/mod/fabric-api) | 0.80.0 | 1   | ✓   | ✓   |
| [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin/) | 1.9.4 + Kotlin 1.8.21 | 1   | ✓   | ✓   |
| [Floodgate](https://github.com/GeyserMC/Floodgate-Fabric) | Build \#98 | 0   | ✓   |     |
| [Geyser](https://geysermc.org/) | Build \#142 | 0   | ✓   |     |
| [Grind Enchantments](https://modrinth.com/mod/grind-enchantments) | 3.0.0 | 1   | ✓   |     |
| [Improved Signs](https://modrinth.com/mod/improved-signs) | 1.2.1 | 0   | ✗   | ✗   |
| [InfiniteVillagerTrading](https://modrinth.com/mod/infinitevillagertrading) | 0.68.1 | 0   | ✗   | ✗   |
| [Inventory Sorting](https://modrinth.com/mod/inventory-sorting) | 1.8.10 | 1   | ✓   |     |
| [Jade](https://modrinth.com/mod/jade) | 10.3.0 | 1   | ✓   | ✓   |
| [JamLib](https://modrinth.com/mod/jamlib) | 0.6.0 | 0   | ✓   |     |
| [Lithium](https://modrinth.com/mod/lithium) | 0.11.1 | 1   | ✓   | ✓   |
| [LuckPerms](https://luckperms.net/) | 5.4.79 | 0   | ✓   | ✓   |
| [No Shield Delay](https://modrinth.com/mod/no-shield-delay) | 1.0.0 | 0   | ✓   | ✓   |
| [Perfect Accuracy](https://modrinth.com/mod/perfect-accuracy) | 1.2 | 0   | ✓   | ✓   |
| [Phosphor](https://modrinth.com/mod/phosphor) | 0.8.1 | 1   | ✗   | ✗   |
| [RightClickHarvest](https://modrinth.com/mod/rightclickharvest) | 3.2.0 | 0   | ✓   | ✓   |
| [TabTPS](https://modrinth.com/plugin/tabtps) | 1.3.17 | 0   | ✗   | ✗   |

Mods currently being considered:

| mod | client | comments | 1.20.0 support | 1.20.1 support |
| --- | --- | --- | --- | --- |
| [Slumber](https://modrinth.com/mod/slumber) | 0 | | ✓   | ✓   |

## Changes made by mods

The changes that each mod makes to the game, to the best of my knowledge.

### AntiXray

Changes information about the world that is sent to the client in order to combat X-ray cheats.

### Anvil Restoration

Right-clicking an anvil with an iron ingot will repair it and consume the iron ingot. <br>
Right-clicking an anvil with obsidian will damage it, but the obsidian will not be consumed.

### Better Than Mending

Sneak + right-clicking while holding an item enchanted with mending will repair the item using XP you already have.

### Bypass Anvil Restriction

Practically removes the 40-level limit for enchanting items with an anvil. <br>
If not installed on the client, this mod will still work and you can enchant any item as long as you have enough levels. However, the text in the anvil will say "Too expensive!" <br>
If installed on the client, you will be able to see the amount of levels you need for the enchant. **(untested)**

### Carpet

[Carpet and Carpet Extra server configs](configs.md#worldcarpetconf) <br>
[Carpet currently available settings (wiki)](https://github.com/gnembon/fabric-carpet/wiki/Current-Available-Settings)

Empty shulker boxes can be stacked. **(untested)** <br>
The delay to go through a nether portal is 10 ticks (0.5 seconds) instead of 80 ticks (4 seconds). <br>
XP is picked up instantly. <br>
Glass can be mined faster with a pickaxe. **(works better with carpet installed on client)** <br>
TNT causes less lag when exploding in the same spot, or in liquid. <br>
Optimizes spawning to use less CPU and memory. <br>
Pistons can move block entites, such as chests and hoppers. **(untested)** <br>

### Carpet Extra

[Carpet and Carpet Extra server configs](configs.md#worldcarpetconf) <br>
[Carpet Extra currently available settings (wiki)](https://github.com/gnembon/carpet-extra)

Allows alternative block placement from clients. **(untested)**

### Cloth Config API

Library mod, dependency for Day Dream.

### Collective

Library mod, dependency for Anvil Restoration.

### Command Aliases

[Command Aliases server configs](configs.md#commandaliases)

Allows making custom commands. Currently used for `/kickme`, `/killme`, and `/nick`.

### Day Dream

Sleeping during the day will make it nighttime.

### Double Doors

Doors, trapdoors, and fence gates now open together when they are next to each other.

### Dynmap

Hosts a real-time map of the server which can be accessed through a browser.

### Essential Commands

[Essential Commands server configs](configs.md#essentialcommandsproperties)

Adds teleportation-related commands to the server, as well as a nickname command.

### Fabric API

Dependency for almost every fabric mod.

### Fabric Language Kotlin

Adds Kotlin compatibility to Fabric. Dependency for Bypass Anvil Restriction and Day Dream.

### Floodgate

Allows Bedrock Edition players to join without a paid Java account, and transfers skins of Bedrock players.

### Geyser

Allows Bedrock Edition players to join a Java Edition server.

### Grind Enchantments

[Grind Enchantments server configs](configs.md#grindenchantmentsjson)

Allows transferring enchantments from items to books and between books with a grindstone.

### Improved Signs

[Improved Signs server configs](configs.md#improved-signsjson5)

Sneak + right-click allows you to edit a sign. <br>
Right-clicking a sign will interact with the block behind the sign.

### InfiniteVillagerTrading

Edits villagers' trades lists to allow for infinite trading.

### Inventory Sorting

If not installed on the client, middle-clicking or double left-clicking on an empty slot of an inventory will sort it. **(Middle-clicking seems to be bugged right now)** <br>
If installed on the client, you can also click the sort button and customize how the inventory is sorted.

### Jade

Gives extra information about the world to those with Jade installed on their fabric clients, including item storage, horse stats, bees in beehives, etc.

### JamLib

Library mod, dependency for RightClickHarvest.

### Lithium

Optimizes many aspects of Minecraft Java Edition.

### LuckPerms

Used for managing permissions.

### No Shield Delay

Removes the delay between putting up your shield and being protected from damage. **(untested)**

### Perfect Accuracy

Removes random inaccuracy from projectiles shot/thrown by players. **(untested)**

### Phosphor

Optimizes the lighting engine of Minecraft Java Edition.

### RightClickHarvest

[RightClickHarvest server configs](configs.md#rightclickharvestjson)

Right-clicking a crop will break and re-plant the crop. Different tiers of hoes will harvest in a different radius.

### TabTPS

[TabTPS server configs](configs.md#tabtpsdisplay-configsdefaultconf)

Displays information about server performance.
