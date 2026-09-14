# One Shot Muse 1.3 xhigh rubics cube

3D Rubik's cube demo page that can scramble and solve the cube visually, turn by turn.

## Run

```sh
python3 -m http.server
# open http://localhost:8000/index.html
```

ES modules + CDN imports require http, not `file://`.

## Features

- Three.js 3D 3x3 cube with orbit/zoom and animated face turns
- Scramble (22 moves), Solve, Reset
- Turn-by-turn stepper: Prev/Next, Play/Pause, speed control, progress bar, move log
- Manual twists (U/R/F/D/L/B + primes), solvable from any state
- True Kociemba two-phase solver (min2phase CDN, ~20 moves) with history-reverse fallback
