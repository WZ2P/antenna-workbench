# WZ2P Antenna Workbench

**HF/VHF antenna design & build planner — dimensions, matching, radiation patterns, and a printable one-page build sheet.**

🔗 **Use it here: [https://wz2p.github.io/antenna-workbench/](https://wz2p.github.io/antenna-workbench/)**

A free, single-file web tool for amateur radio operators. Enter a frequency and antenna type, and get validated cut dimensions, a labeled build drawing, matching/balun recommendations, feed line loss, radiation patterns, and a shopping list — ready to print and take to the garage. Runs in any browser on any device. No installation, no account, works offline once loaded.

## Antenna Types

**HF:** half-wave dipole · inverted-V · end-fed half-wave (EFHW) · fan dipole · full-wave loop · ¼-wave vertical (ground-mounted or elevated) · 3-element Yagi

**VHF/UHF (10 m & up):** J-Pole · Slim Jim · ⅝-wave ground plane · Moxon rectangle — with construction options for copper pipe, 450 Ω window line, and 300 Ω twin-lead, each with the correct velocity factor applied.

## Features

- **Cut dimensions** in US (ft/in) or metric, with material velocity factors and conductor-diameter corrections
- **Build drawings** with every segment measured, including calculated feed-point locations showing exactly where the coax center conductor and shield connect
- **Radiation patterns** (elevation and azimuth) with a live height slider — validated against NEC-2, the same engine as EZNEC
- **Site advisor** tailored to your yard size, height, and soil quality, with honest alternatives when the ideal won't fit
- **Radial system planner** for verticals, from broadcast-grade to "get on the air" tiers
- **Feed line loss budget** using manufacturer-fitted attenuation models (Times Microwave form), plus SWR curve and mismatch loss in expert mode
- **Expert mode:** construction recipes (unun/balun winding, hairpin & gamma match values, loading coils), wire sag & tension, FCC OET-65 RF exposure screening
- **🖨 Print Plan:** one-page build sheet — drawing, dimensions, and shopping list — with print preview
- **🎲 Surprise me!** — press at your own risk. Wilmington hams, you've been warned.

## Quick Start

1. Open the tool and enter your yard size when asked (remembered on your device)
2. Pick a band and antenna type
3. Drag the height slider and watch the pattern change
4. Hit **Print Plan** and go build it

Dimensions are validated starting points from proven formulas (468/f family, M0UKD-form VF scaling) cross-checked against NEC-2 modeling and published attenuation data. As always: **cut long, trim to resonance.**

## Running Locally

Download `index.html` and double-click it. That's the whole program.

---

*Software written by WZ2P Rich Leland, NC. Built for the amateur radio community — share it with your club. 73!*
