# P5 Fish Sketch 🐟

A p5.js sketch of a school of fish swimming across an underwater scene, from left to right.

## Run it

Just open `fish.html` in a browser — no build step needed (p5.js loads from a CDN):

```sh
open fish.html
```

## What's in the scene

- **Fish** — 12 fish with random size, speed, and color. Small fish dart faster than big ones. Tails wag, bodies bob, and fish wrap back to the left edge when they exit the right.
- **Scenery** — water gradient, sandy bottom, swaying seaweed, drifting light rays, and rising bubbles (occasionally blown out of a fish's mouth).

## Easy tweaks (in `fish.html`)

| What | Where |
|---|---|
| Number of fish | the `12` in `setup()` |
| Speed range | `random(1.5, 3)` in the `Fish` constructor |
| Fish colors | `this.hue = random(360)` — e.g. `random(180, 220)` for blue reef fish |

## Tech

Single self-contained HTML file: [p5.js](https://p5js.org/) via CDN, no dependencies or build tools.