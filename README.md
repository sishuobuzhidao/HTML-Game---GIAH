# HTML-Game---GIAH

**Attribution**
Original game engine and some assets: qq_45726626 — https://blog.csdn.net/qq_45726626/article/details/102514441 (licensed under CC BY‑SA 4.0).  
My contributions: level designs and original music by sishuobuzhidao (GitHub) & my friend cmd.  
This repository is distributed under the Creative Commons Attribution‑ShareAlike 4.0 International (CC BY‑SA 4.0) license. See LICENSE for details.

**If you reuse code from this repo**
1. Keep the attribution (original author + link).  
2. Indicate your changes.  
3. Distribute derivative works under CC BY‑SA 4.0.

**Contact**
- Repo owner / levels & original music: sishuobuzhidao (GitHub)
- Original CSDN post: https://blog.csdn.net/qq_45726626/article/details/102514441
- License: https://creativecommons.org/licenses/by-sa/4.0/

**Mechanics**
This game is a parkour game with 13 levels. One has 20 lives, and the goal is to pass all the levels. Levels are designed in May 2022 and November/December 2022. The music link on the top is composed by sishuo in 2022.

**Keybinds**
Press WSD for jump/left/right;
Press left/up/down arrow for jump/left/right;
Press Z for skipping level (cost 5 lives);
Press R for retry same level (cost 1 live).

**In-game elements**
1) Player: Controllable;
2) Walls: Blocks that can stand on, cannot walk past;
3) Lava: In the game there are static lava and dynamic lava. For both types, upon touching the player will die. Static lava behaves like walls (the player can stand on and   cannot walk past them), while dynamic lava moves. Most dynamic lava moves vertically or horizontally (with different velocity), but some will move diagonally;
4) Coins: This is the most intricate part of the game design. In the open-source game, coins can be collected. However, in this version, when touching a coin that appears gold, the player will die and fail the level (unless you touch the destination fast enough). Players can collect fruits across the map. If all fruits situated in the map are collected, the coins will turn red and become harmless (i.e. the player can walk past them, but not collectable);
5) Fruits: Collectable throughout the map. If all fruits situated in the mao are collected, coins will become harmless. However, fruit collecting is not compulsory, i.e. players can still pass the level by touching the destination without collecting all the fruits;
6) Destination: Looks like a flag. Upon touching, the player passes the current level and will move on to the next one;
7) Fake Walls: Some "walls" are actually fake walls that, upon touching, will disappear. This is prominent in the Tunnel level;
8) Door: A type of wall that, upon touching, makes some other doors invisible (This was a immature design that was used rarely);

**Levels**
For the most popular version, there are 13 levels in total
1) Welcome
2) Double Jumps
3) Spinning Jumps
4) Bonus: GIAH
5) 01: Cornered by Lava
6) 02: Looking for the Destination
7) 03: The Super Channel
8) The Volcano
9) The Tunnel
10) The Boss Level
11) The Lava of Meteors
12) The Castle
13) 04: Insane Fruit Collecting

Level mostly designed by sishuo and cmd. 01, 02, 03 and 04 contains fragments and characteristics of the source file, but the levels are changed greatly from the original version.
