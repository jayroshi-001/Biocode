# BIOCODE v3.7

Real-time 3D ASCII double helix rendered in the browser. No dependencies. No canvas. Just characters.

## What it does

BIOCODE renders a high-poly DNA double helix using ASCII characters with full 3D depth simulation — z-buffered shading, perspective projection, base pair bonds (A-T, G-C), and phosphate backbone particles. Everything runs in a single HTML file.

## Features

- Z-buffered depth rendering (characters scale from · to █ based on proximity)
- Perspective-projected dual strands with sub-pixel fill
- Base pair ladder rungs with nucleotide labels
- Phosphate backbone particle system
- 5 color themes: Phosphor, Cyber, Amber, Synthwave, Matrix
- Fully interactive keyboard controls
- CRT scanline + vignette terminal aesthetic
- Zero dependencies — one HTML file, open and run

## Controls

| Key | Action |
|-----|--------|
| ↑ ↓ | Rotation speed |
| ← → | Twist tightness |
| + - | Helix radius |
| Space | Pause |
| C | Cycle color themes |

## Run it

Open `biocode.html` in any modern browser. That's it.

## Built with

Human-AI collaboration using Claude. One prompt, one artifact, zero boilerplate.

## License

MIT
