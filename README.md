# Minecraft Telemancer
> Just a simple script to calculate overworld jump achieved using ender pearl saving and chunk loading!! It works on the principle that ender pearl when thrown finds target coordinates and teleport players to there, without checking dimension, So the nether 8:1 block ration actually makes you travel 8*CurrentWorldCoords (Both X and Z) instantly, It is quite godly trick to travel thousands if not millions blocks effortlessly!!

Detailed posts and mechanism:
 1. https://www.minecraftforum.net/forums/minecraft-java-edition/redstone-discussion-and/346813-long-distance-ender-pearl-teleportation
 2. https://www.minecraftforum.net/forums/minecraft-java-edition/survival-mode/285261-long-distance-ender-pearl-teleportation-tutorial

## Script
Script: **overworld_to_nether.py**
```
1. Just open the python script and enter your current X and Z coords.
2. After inputting coords, throw ender pearl in the sky and quickly teleport via nether portal!
3. Have another account or something which can load current overworld chunk! VOILA! You are teleported to somewhere far in nether! (*Final Nether Coords* in script),
4. Make another nether portal here and go to overworld, VOILA! You just travelled 8 times your previous overworld coordinates there ><!! (*Nether equivalent overworld Coords* in script)
```

## Output
> Just a simple output of program
Script: **overworld_to_nether.py**
```
Enter overworld X:1000
Enter overworld Z:1000
[USELESS]Expected nether(initial) X: 125.0
[USELESS]Expected nether Z(initial): 125.0
Final Nether X: 1000
Final Nether Z: 1000
Nether equivalent overworld X: 8000
Nether equivalent overworld Z: 8000
```
