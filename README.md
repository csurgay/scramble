# scramble
Remake of the 1981 Konami arcade game of bombing FUEL tanks...

HTML5 canvas, plain JavaScript, a single file: open `index.html` in a browser.

## Controls
| Key | Action |
| --- | --- |
| Enter / 1 | start |
| arrows | fly |
| Z / Space | laser |
| X / C | bomb |
| P / Esc | pause |
| M | sound on/off |

On touch screens an on-screen pad appears.

## What follows the arcade
- 224×256 portrait screen, 60 Hz, the ship scrolls right at a constant speed
- six sections: mountains (rockets take off), cave (UFOs), fireballs (cannot be shot), city, maze, base
- fuel runs out over time, bombing or shooting FUEL tanks refills it; out of fuel the ship sinks
- scoring: 10 pts/second of flight, rocket 50 on ground / 80 in the air, UFO 100, fuel tank 150, mystery 100/200/300, base 800
- 3 ships, extra ship at 10 000, a crash restarts the current section
- destroying the base adds a mission flag and starts the next round with faster fuel use
- the map is the same every round, so it can be learned

Sprites and sounds are original, not taken from the arcade ROMs.
