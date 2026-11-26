# FAL125 Clash

A 1v1 fighting game that uses fighters from the FAL125 game
(<https://github.com/jtanis2009-design/Fal-125-Project-game>). The characters,
names, move names and sprites all come from the FAL125 Character Book.

Open `index.html` in a browser. It needs the `img/` folder next to it.

## Version 4
- 20 fighters (a 5 by 4 select screen): Radiant, Fuja, Eyianix and Bearer (the story's main four),
  Chaser, Ixis, Soundemon, The Red Walker, Hemo, Renku, Parda, Weeping Angel, Glacier, Copyright,
  Lycion, Tomb, Toon, Flick, Uquna and Marrowline. Doommaster and Unbreakable were swapped out
  for Fuja and Flick (their code is still in the git history).
- Each fighter has one mechanic only they have (for example parry, freeze, copy, rage form,
  gasoline pools, random gags, swallowing shots, reversed controls, eye drones, demon spawn,
  grabs, and a Red X cannon).
- Skins come from FAL125: every fighter has its two named FAL125 recolours (for example Radiant's
  Hazard Yellow and Fallout Pink). Fuja, Radiant, Eyianix, Bearer and Renku also have their drawn
  FAL125 art skins (Horror Drawing, Scribble Original, Classic, Legendary) in `img/skin_*.webp`.
- Select screen: fighter art on both sides with name plates, a face grid, a tips bar and a button
  bar. Keyboard: move the cursor, press confirm to pick, choose a colour left/right, confirm again
  to lock in. In 2 Players both players pick at the same time.
- Fuja, Flick, Eyianix and Bearer only have a standing sprite so far. The game leans them forward
  when they attack and flattens them when knocked out. To give them real poses, save
  `img/<key>_atk.webp` and `img/<key>_ko.webp` (keys: fuja, flick, eyianix, bearer); the game
  uses them automatically.

## Controls
| | Player 1 | Player 2 |
|---|---|---|
| Move | A / D | Left / Right arrow |
| Jump | W | Up arrow |
| Block (hold) | S | Down arrow |
| Light | J | , or Num 1 |
| Heavy | K | . or Num 2 |
| Special | L | / or Num 3 |
| Super | I | Right Shift or Num 0 |

Esc or P pauses. M turns the sound on and off.

## Adding a fighter
Copy `<key>.webp`, `<key>_atk.webp` and `<key>_ko.webp` from the FAL125 `img/` folder
into `img/`, then add an entry to `ROSTER` in `index.html`.
