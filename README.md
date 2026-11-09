# APEX — Racing Sim

Browser racing sim (three.js).

- Race and Practice on six circuits: Spa, Shanghai, Nürburgring GP, Bahrain, Yas Marina, Marina Bay
- Free drive: open world (hills, roads, towns, forests) with a stunt park at the centre
- Drift: flat arena with ramps and trick scoring
- 19 car models; manual gearbox and manual brakes. If a model file can't load, the game uses a built-in model instead.

## Play
Host it on GitHub Pages (Settings → Pages → Deploy from a branch → `main` / `/ (root)`) or run
`python3 -m http.server` in this folder. It must be served over http(s); opening `index.html` directly
from disk can't load the model files (the built-in models are used instead).
Needs internet for the three.js library (cdnjs / jsDelivr).

## Credits
Created by Cavan, Derek, and Rihaan. 3D models are third-party assets; check each licence before redistributing.
