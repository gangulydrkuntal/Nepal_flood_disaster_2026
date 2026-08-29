# Langtang Lirung Glacier Collapse — Geospatial Reconstruction

By **Kuntal Ganguly**

A story map reconstructing a glacier collapse at Langtang Lirung, Nepal, on the
Nepal–Tibet (China) border, using elevation, slope, and area measurements taken
from Google Earth against pre-event imagery.

## Contents

| File | Purpose |
|---|---|
| `index.html` | The story map. Self-contained apart from the video. |
| `corridor_flythrough.mp4` | Pre-disaster 3D flythrough of the Bhote Koshi–Trishuli corridor. |

Both files must sit at the same level — `index.html` references the video by
relative path.

## Publishing on GitHub Pages

1. Push these files to the repository root (or to a `/docs` folder).
2. Repository **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then **Save**.
5. The site goes live at `https://<username>.github.io/<repo-name>/` after a
   minute or two.

## Scope and disclaimer

This study includes **no post-disaster imagery**. It approaches the event by
examining the geographic and land-use conditions in the region as they existed
*before* the collapse — terrain, slope, glacier extent, drainage geometry, and
the pattern of development along the corridor.

All imagery, elevation profiles, slope values, areas, and distances are derived
from **Google Earth** (imagery data attribution as captured, 01 July 2026) using
its Measure, Path, and Elevation Profile tools. Figures are reconnaissance-level
estimates, constrained by the resolution and vintage of the underlying imagery
and elevation model, and carry the uncertainty inherent in manual on-screen
measurement — particularly on steep headwalls.

Distances quoted are what was measured, not necessarily the full extent of the
event: the debris path was traced to roughly 30 km, which is where the
measurement stops rather than where the debris stopped.

This is not an official hazard assessment, survey, or damage report, and should
not be used as one.
