# RUBICON
mechanics blueprint sandbox under construction

## Isometric KABBA simulator

This repository now includes a lightweight browser-based isometric KABBA simulator with chunky neon
graphics inspired by a t3ssl8tr-style presentation.

### Run locally

Because the prototype is dependency-free, you can serve it with any static file server. For example:

```bash
cd RUBICON
python3 -m http.server 8000
```

Then open `http://127.0.0.1:8000/` in a browser.

### Controls

- Click a tile to select it, then click it again to raise that KABBA tower
- Shift-click or right-click a tile to lower it
- Use the on-screen controls to pause, resume, or reset the pulse
- Press `Space` to pause/resume, `ArrowUp` to raise, and `ArrowDown` to lower
