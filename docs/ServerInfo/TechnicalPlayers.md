# Information for Technical Players

We have made a number of changes to key behaviour in order to make the server more performant. In most cases this should be invisible players, however for technical players this information may be critical when building certain types of farms.

Many of the settings we have changed come from this [server optimization guide](https://www.spigotmc.org/threads/guide-server-optimization%E2%9A%A1.283181/) on the Spigot forums, but there are several other tweaks we've made that aren't listed there. Performance is a massive priority so that all players can have a good experience. I hope the information here can help you have a great time as a technical player.


## Map Pregeneration

In order to decrease lag, we have pregenerated all chunks within the 10k world border. If there is ever a significant overworld content update, any chunks that don't have player-built structures on them may be deleted.

## Mob Spawn Limits

We have decreased the number of mobs that spawn in a given area from 70 to 50, however we have also decreased the size of these areas. This means that although the amount of mobs that spawn in an area is decreased, more areas fit in the same amount of space meaning for the average player there won't be a noticable difference in how many mobs spawn.

The normal mob spawn range is 8 chunks (128 blocks) but we have reduced it to 6 chunks (96 blocks). This means that any farms you build that rely on you standing nearby to allow the mobs to spawn may need to be revised for you to stand closer.

Despawn range has been changed from 128 to 96 blocks. So mobs further than 96 blocks away from you will be removed instantly.