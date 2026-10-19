# Field Notes — independent terrain study

Eight seconds, 1920 × 1080, 30 fps. A synthetic route climbs a sculptural contour terrain and unfolds into an altitude profile. All geographic data are fictional. This is an independent visual study, not client work or evidence of a commissioned documentary.

## Watch

[Watch the study](https://btusbefw.github.io/expedition-terrain-study/) or download terrain-study.mp4.

## Editable source and render

The actual source is composition.html (HTML, SVG geometry and a single paused GSAP timeline). It is not a native After Effects project. Geometry is deterministic trigonometry, with no random generator, external map or real location. Typography uses generic sans-serif and monospace. GSAP is pinned to 3.14.2 and HyperFrames to 0.8.174.

Copy composition.html to index.html in a separate working folder, alongside package.json, then run `npm run check` and `npx --yes hyperframes@0.8.174 render --quality delivery --fps 30 --output terrain-study.mp4`. Do not replace the landing page when simply hosting the video.

Palette: ink #0A0B0D, layered stone, ice #E6EDF2, route #FF5A1F. Fictional base 2140 m, summit 5870 m, gain 3730 m, distance 8.4 km. The final profile retains only base, summit and distance labels. Decorative titles and scale grids are omitted so the route remains the subject. The independent/synthetic disclosure is on the viewing page, outside the film.

## Verification

Runtime, layout, motion and contrast checks passed. One lint warning is accepted: this short unit is authored as one SVG-containing scene rather than a mounted sub-composition. Output metadata: 8.0 seconds, 240 frames, 1920 × 1080, 30/1 fps. Decoded output inspected at one-second intervals and across the route-to-profile transition, with 320 × 180 thumbnail review.

CDRXRX · dev@dbrx.fr
