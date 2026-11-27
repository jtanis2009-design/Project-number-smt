# FAL125 Clash

A 1v1 fighting game that uses fighters from the FAL125 game
(<https://github.com/jtanis2009-design/Fal-125-Project-game>). The characters,
names, move names and sprites all come from the FAL125 Character Book.

Open `index.html` in a browser. It needs the `img/` folder next to it.

## Version 5
- 31 fighters in 3 rows of 11. Clown.x25 has a short health bar and splits into his two mini
  forms (the armour and the doll) on his first knockout each round. Also: Rainbow Ripper, Gloom, Dollion, Vein Ripper, Stitchheart, Glitch, Hush,
  Serpentine, Sunburst and Walker joined (Furnace and The Painter were swapped out; their code is
  in the git history). Flick was reworked from the author's sheet (Flipside stores and transfers
  damage, Look Inside stuns) and uses its new FAL125 sprites (V307).
- Each fighter has one mechanic only they have (for example parry, freeze, copy, rage form,
  gasoline pools, random gags, swallowing shots, reversed controls, eye drones, demon spawn,
  grabs, and a Red X cannon).
- Skins come from FAL125: every fighter has its two named FAL125 recolours (for example Radiant's
  Hazard Yellow and Fallout Pink). Fuja, Radiant, Eyianix, Bearer and Renku also have their drawn
  FAL125 art skins (Horror Drawing, Scribble Original, Classic) in `img/skin_*.webp`.
- 11 stages, one for each FAL125 world (The Broadcast is Freedom at a Price): Containment Hall B, The Showroom (Experimental Ringer),
  Sewer Network, The Perimeter Fence (Beyond the Facility), The Safe Haven, Something Isn't Right,
  The Altar (The Cult), The Tape (The Climax), The Big Top (Clown's Massacre) and The Casino Floor.
  Pick one on the select screen (Q / E or the arrows), or leave it on Random.
- Select screen in a FAL125 containment-terminal style: subject cells, ID numbers, hazard tape,
  a CLEARED stamp and a facility log. Keyboard: move the cursor, press confirm to pick, choose a colour left/right, confirm again
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
