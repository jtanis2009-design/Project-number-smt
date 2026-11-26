# FAL125 Clash

A 1v1 fighting game that uses fighters from the FAL125 game
(<https://github.com/jtanis2009-design/Fal-125-Project-game>). The characters,
names, move names and sprites all come from the FAL125 Character Book.

Open `index.html` in a browser. It needs the `img/` folder next to it.

## Version 1
- Fighters: Radiant, Chaser, Doommaster and Ixis. Each has a light attack, a heavy attack,
  a special and a super, plus their own meter (RAD, Speed, Doom, Store).
- Modes: 1 player against the computer (Easy, Normal or Hard), or 2 players on one keyboard.
- Best of 3 rounds with a 99-second timer. On phones, touch buttons appear.

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
