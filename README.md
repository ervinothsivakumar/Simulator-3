# G+2 Collapse Rescue Simulator

A browser-based, first-person training simulator for building-collapse search and rescue.

- **Module 1 · Equipment training** – a walled yard with eight guided lessons: fire alarm call point, extinguisher types and the safety pin, mains isolation, crowbar forced entry, casualty lift and carry.
- **Module 2 · Rescue drill** – an earthquake-damaged G+2 RC frame building with six casualties (locations change each run), three classes of fire, live mains, jammed doors and aftershocks. Scored out of 100.
- **Trainee report** – scores, event log, rescuer track and instructor remarks; print or save as PDF, or download as HTML.

## Run it

Open `index.html` through a web server (GitHub Pages works as-is). An internet connection is needed because the 3D library loads from a CDN.

## Host on GitHub Pages

1. Upload every file in this folder to the root of a public repository.
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
3. The simulator is live at `https://<username>.github.io/<repository>/` after a minute or two.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The simulator (menu, both modules, report) |
| `drill.json`, `drill-model.json` | Collapse site: game data and 3D model |
| `yard.json`, `yard-model.json` | Training yard: game data and 3D model |

Scoring weights and extinguisher rules are illustrative training defaults; adjust them to your organisation's standard before using the report for assessment.
