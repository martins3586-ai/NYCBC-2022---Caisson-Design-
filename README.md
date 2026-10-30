# NYC Caisson Calc – 2022 Edition

Design checks for rock-socketed drilled caissons to the 2022 New York City Building Code (Chapter 18), allowable stress design.

## What it does

- **Loads:** service load (dead + live), other compression, downdrag and net uplift.
- **Geotechnical:** required rock socket length from skin friction (rock class along the socket) with optional end bearing (rock class at the tip), FS 2 compression / FS 3 tension. Governing length is the largest of the geotechnical length, the NYC BC 1812.7.3 minimum, shear stud transfer length and threadbar development length.
- **Structural:** allowable axial capacity of the cased shaft and uncased socket per Table 1810.8 (concrete, AISC W/HP steel core, permanent casing, threadbar).
- **Reinforcement:** steel core with web and/or flange shear studs; Nucor Skyline Grade 80 threadbar as a central bundle (up to 4 bars) or one or two circular rings (bundles up to 3), with coupler layout checks.
- **Code checks:** NYC BC 1812.7 steel area limits (core ≤ 30% of gross area, perimeter bars ≤ 8% of area inside casing), f′c, casing wall, rock class.
- **Drawings:** profile and cased/socket cross sections.
- **Calc package:** PDF export with your logo bottom-left on every page.
- **Saved designs and templates:** stored in your browser.

## Limitations

Checks the axial capacity of a single caisson only. Lateral capacity, group effects, slenderness and bending are not checked and must be evaluated separately. Verify all defaults against the code and the project geotechnical report.

## Running it

It is a single static file, `index.html`, with no build step. Open it in a browser, or serve it with GitHub Pages (Settings → Pages → Deploy from branch → `main`, folder `/`).

## Data sources

- AISC Shapes Database v15.0 (W and HP shapes)
- Nucor Skyline 2026 Technical Product Manual (threadbar areas, thread and coupler diameters)
- 2022 NYC Building Code Chapter 18; ACI 318-19; AISC 360-16
