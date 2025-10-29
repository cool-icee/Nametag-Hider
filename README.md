# Nametag-Hider-Minecraft-
This is a lightweight Minecraft Datapack that hides nametags in multiplayer.

# Note
This Datapack uses a team to create the effect of the hidden name, so you must remove the datapack and revert all changes to make players be able to join other teams.

# Process
This datapack first makes a team named ```hidename```, then forces all players within the world to join that team not be able to leave. Afterwards, it modifies the team using the command```/team modify hidename nametagVisibility never```. This command makes the members of ```hidename``` not be able to view each other's name tags. It also modifies the team so the datapack is still usable in anarchy servers.
```
team add hidename
team modify hidename nametagVisibility never
team modify hidename seeFriendlyInvisibles false
team modify hidename friendlyFire true
team modify hidename collisionRule always
```
