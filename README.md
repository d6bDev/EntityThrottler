# EntityThrottler

**Made for STANDAPI**

A better entity throttler & filter, designed to prevent people from spamming you with entities and triggering spam crash protection, possibly locking your camera if the spam doesn't cease or worse yet - causing a crash.

Includes many customizable filters:

**Auto Throttler**
The simplest to use, this filter will consider all entities synced by any player and has the ability to set a total limit of entities synced by any given player, a model limit of entities with identical models synced by any given player as well as a high limit to limit the amount of high priority (mission) entities synced by any given player.

**Big Vehicle Throttler**
This filter will automatically remove all instances of vehicles considered "big" (e.g. cargoplane, volatol, kosatka) synced by an affected player, as well as block the affected players incoming syncs for a set timeout duration, if a set limit of big vehicles is exceeded by the affected player

**Ped, Vehicle, Object Throttlers**
These are harder to set up but pretty self explanatory, might yield better results than the auto throttler if set up properly.
