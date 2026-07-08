# LVL5-Game-5D
5D puzzle built with golden toroidal-Taurus math game
# LVL5

Pentomino puzzle that climbs from 2D to 5D. One HTML file. Zero
dependencies. No build step, no server, no tracking, no network calls.

**Play now: https://lvl5.hom3.org**

![gameplay](media/lvl5.gif)

## What it is

Five levels, one per dimension:

- **LVL 2** -- classic pentominoes on a 2D field
- **LVL 3** -- pentacubes in 3D
- **LVL 4** -- 4D play, projected down to your screen
- **LVL 5** -- the finale: five dimensions, driven by an isoclinic
  double rotation -- a rotation in two orthogonal planes at once, a
  motion that cannot exist below four dimensions


The engine is dimension-generic: the same placement, collision, and
rotation code runs every level, parameterized by dimension.

Other mechanics:

- Fibonacci scoring 
- Torus topology -- the field wraps modeled after torroidal

## Controls

Higher dimensions require more controls- fill in controls -- keys/touch, rotate, drop, plane-select in
higher dimensions

## Run locally

Download `index.html`. Open it in a browser. That is the entire install.

## Technical notes

[
- Projection chain: 5D -> 4D -> 3D -> screen 
- How rotation planes are enumerated per dimension 
- Rendering approach (canvas/WebGL, wireframe/solid) 

## Why

Built as a study in dimension-generic geometry: how far up the
dimension ladder can a falling-block puzzle stay playable? This is the
first public release from roughly twenty years of private code.

## License

MIT -- Copyright (c) 2026 HOM3 Technologies LLC

---

Built by Paul Krause -  [HOM3](https://hom3.org -- sovereign personal computing.
Hardware: the HOM3 Deck .-.

1<3
