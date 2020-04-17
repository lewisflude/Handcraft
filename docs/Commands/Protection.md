# Protection

## Plugins

* [GriefDefender](https://github.com/bloodmc/GriefDefender/wiki)
* [LWC Extended](https://www.spigotmc.org/resources/lwc-extended.69551/)

## Land Claiming

Every player has the ability to claim land. You do this using claim blocks. Each claim block allows you to claim one block of land from bedrock to build limit. So a 10x10 area from bedrock to build limit would cost 100 claim blocks.

Players start with 120 claim blocks and earn 120 more per hour in-game. You can also buy extra claim blocks if you want to claim a larger area.

When you place a chest, the land surrounding it will be automatically claimed and will automatically expand as you expand your build.

You can also change flags on claims you own in order to toggle certain behaviours including whether PVP is allowed, animal spawning, water flow and more!

### How to make a claim
The most efficient way to create a claim is using a golden shovel. When holding a golden shovel you will see how many claim blocks you have available. You right click in the first corner of your claim, and then right click in the second corner to create your claim.

### How to resize a claim
The golden shovel is also used to resize a claim. Right click once in an existing claim to see the corner markers. Right click on a corner block and then again on a different position to move that corner.

### How to delete a claim
Use the `/abandonclaim` command while standing in a claim.

### Commands
- `/claim` Start the claiming process
- `/claiminfo` Show information about the claim you are in
- `/claimflag` Set flags in a claim you own
- `/trust <player>` Allow another player to build in your claim
- `/buyblocks <amount>` Buy additional claim blocks for $2/block
- `/abandonclaim` Abandon a claim you are standing in

## Chest Protection

### Commands
- `/lock` Lock a chest
- `/unlock` Unlock a chest 
- `/cpublic` Lock a chest, but anyone can open it
- `/cpassword <password>` Lock a chest, but it requires a password to open it
- `/cmodify <player>` Allows another player to open a locked chest
- `/chopper <on|off>` Enable or disable hopper usage to a locked chest
- `/cpersist` Make the previous chest command persist
