## Modlist

This is a list of fabric mods currently installed on the server. None of these need to be downloaded for you to join the server or for the mods to work as intended. <br>
Client support may not be completely accurate in regards to the server.

0 = unsupported/unnecessary, 1 = optional, but recommended, ? = unknown

| mod | version | client | 1.19.4 support |
| --- | --- | --- | --- |
| [AntiXray](https://modrinth.com/mod/anti-xray) | 1.3.0 | 0 | &check; |
| [Anvil Restoration](https://modrinth.com/mod/anvil-restoration) | 2.0 | 0 | &check; |
| [Better Than Mending](https://modrinth.com/mod/better-than-mending) | 1.3.0 | 0 | &check; |
| [Bypass Anvil Restriction](https://www.curseforge.com/minecraft/mc-mods/bypass-anvil-restriction) | 1.0.2 | 1 | &check; |
| [Carpet](https://modrinth.com/mod/carpet) | 1.4.96 | 1 | &check; |
| [Carpet Extra](https://github.com/gnembon/carpet-extra) | 1.4.91 | 0 | &check; |
| [Cloth Config API](https://modrinth.com/mod/cloth-config/) | 9.0.94 | 0 | &check; |
| [Collective](https://modrinth.com/mod/collective) | 6.53 | 0 | &check; |
| [Command Aliases](https://modrinth.com/mod/commandaliases) | 1.0.0 | 0 | &cross; |
| [Couplings](https://modrinth.com/mod/couplings) | 1.9.2 | 1 | &cross; |
| [Day Dream](https://modrinth.com/mod/day-dream) | 1.0.6 | 0 | &cross; |
| [Dynmap](https://www.curseforge.com/minecraft/mc-mods/dynmapforge) | 3.5 Beta 2 | 0 | &check; |
| [Essential Commands](https://modrinth.com/mod/essential-commands) | 0.32.0 | 0 | &check; |
| [Fabric API](https://modrinth.com/mod/fabric-api) | 0.76.0 | 1 | &check; |
| [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin/) | 1.9.2 + Kotlin 1.8.10 | 1 | &check; |
| [Floodgate](https://github.com/GeyserMC/Floodgate-Fabric) | Build #93 | 0 | &check; |
| [Geyser](https://geysermc.org/) | Build #1321 | 0 | &check; |
| [Grind Enchantments](https://modrinth.com/mod/grind-enchantments) |  3.0.0 Beta 1 | 1 | &cross; |
| [Improved Signs](https://modrinth.com/mod/improved-signs) | 1.2.1 | 0 | &cross; |
| [InfiniteVillagerTrading](https://modrinth.com/mod/infinitevillagertrading) |  0.68.1 | 0 | &cross; |
| [Inventory Sorting](https://modrinth.com/mod/inventory-sorting) | 1.8.10 | 1 | &check; |
| [Jade](https://modrinth.com/mod/jade) | 9.4.1 | 1 | &check; |
| [JamLib](https://modrinth.com/mod/jamlib) | 0.6.0 | 0 | &check; |
| [Lithium](https://modrinth.com/mod/lithium) | 0.11.1 | 1 | &check; |
| [LuckPerms](https://luckperms.net/) | 5.4.66 | 0 | &check; |
| [New Infinity Fix](https://modrinth.com/mod/new-infinity-fix) | 1.0.1 | 0 | &cross; |
| [No Shield Delay](https://modrinth.com/mod/no-shield-delay) | 1.0.0 | 0 | &check; |
| [Perfect Accuracy](https://modrinth.com/mod/perfect-accuracy) | 1.2 | 0 | &check; |
| [Phosphor](https://modrinth.com/mod/phosphor) | 0.8.1 | 1 | &cross; |
| [RightClickHarvest](https://modrinth.com/mod/rightclickharvest) | 3.1.0 | 0 | &check; |
| [TabTPS](https://modrinth.com/plugin/tabtps) | 1.3.16 | 0 | &cross; |

Mods currently being considered:

| mod | client | comments | 1.19.4 support |
| --- | --- | --- | --- |
| [Slumber](https://modrinth.com/mod/slumber) | 0 | | &check; |

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

Allows alternative block placement from clients.

### Cloth Config API

Library mod, dependency for Day Dream

### Collective

Library mod, dependency for Anvil Restoration

### Command Aliases

[Command Aliases server configs](configs.md#commandaliases)

Allows making custom commands. Currently used for `/kickme`, `/killme`, and `/nick`.

### Couplings

Opposing doors/trapdoors and vertically stacked fence gates open together when used by a player or powered by a redstone signal strength >7. <br>
They will not open together when the signal strength is <8. <br>
**(Redstone untested)**

### Day Dream

Sleeping during the day will make it nighttime.

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

### New Infinity Fix

Removed the need to have an arrow in your inventory to use a bow enchanted with infinity.

### No Shield Delay

Removes the delay between putting up your shield and being protected from damage.

### Perfect Accuracy

Removes random inaccuracy from projectiles shot/thrown by players.

### Phosphor

Optimizes the lighting engine of Minecraft Java Edition.

### RightClickHarvest

[RightClickHarvest server configs](configs.md#rightclickharvestjson)

Right-clicking a crop will break and re-plant the crop. Different tiers of hoes will harvest in a different radius.

### TabTPS

[TabTPS server configs](configs.md#tabtpsdisplay-configsdefaultconf)

Displays information about server performance.
