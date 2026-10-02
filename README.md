# 3D Car — Browser-Based 3D Car Racing Game

A fully client-side 3D car racing/driving game built with Three.js, playable directly in the browser with no build step and no backend.

## Features

- Real-time 3D car scene rendered with **Three.js** (r132) — WebGL, no plugins required
- Orbit camera controls via `OrbitControls`
- Touch-friendly joystick input via **nipplejs** (mobile support)
- Styling with **Tailwind CSS** (CDN)
- Loading screen, stats monitor, and fullscreen canvas game container
- GLTF/DRACO loaders wired for 3D model assets
- Runs entirely from a single HTML file — zero dependencies to install

## Tech Stack

- Three.js 0.132.2 (WebGL rendering, orbit controls, model loaders)
- Tailwind CSS 2.2.19
- nipplejs 0.9.1 (touch joystick)
- Vanilla HTML / CSS / JavaScript — no bundler, no framework

## Quick Start

Option 1 — open locally:

```bash
git clone https://github.com/girishlade111/3d-car.git
cd 3d-car
# open index.html in any modern browser
```

Option 2 — play online:

https://girishlade111.github.io/3d-car/

## Project Structure

```
3d-car/
├── index.html      # The entire game — markup, styles, and Three.js logic
├── LICENSE        # MIT license
└── README.md       # This file
```

## Deploy Notes

The game is a single static HTML file with all dependencies loaded from CDN, so it can be hosted on any static host (GitHub Pages, Cloudflare Pages, Netlify) with zero configuration — just serve `index.html`.

## License

MIT — see [LICENSE](LICENSE).

---

**Built by Girish Lade** · [ladestack.in](https://ladestack.in)
