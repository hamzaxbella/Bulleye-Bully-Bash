# BullEye Bully Bash

A bull-themed Canvas arcade experiment with collision effects, score tracking, and a defense meter.

[Open the demo](https://hamzaxbella.github.io/Bulleye-Bully-Bash/) · [Browse the code](https://github.com/hamzaxbella/Bulleye-Bully-Bash)

## Play

Click the canvas to set the bull's target. Use `R` to restart and `D` to toggle the debug view. The source contains a score target of 100 and a game-over screen.

The current mouse input updates the target on press/release; continuous drag behavior still needs refinement. This is a desktop mouse-and-keyboard experiment, with no online leaderboard or audio system implemented.

## Run locally

```bash
git clone https://github.com/hamzaxbella/Bulleye-Bully-Bash.git
cd Bulleye-Bully-Bash
python3 -m http.server 8000
```

Open <http://localhost:8000> in a modern browser. There is no package installation or build step.

## Inside

| File | Purpose |
| --- | --- |
| `script.js` | Entity classes, collisions, input, scoring, and drawing |
| `index.html` | Canvas and sprite assets |
| `style.css` | Presentation |
| `assets/` | Game images |

Built with plain JavaScript and Canvas 2D. Included artwork retains its original ownership.
