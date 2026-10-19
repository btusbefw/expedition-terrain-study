# Expedition terrain study

Eight seconds, 1920 × 1080, 30 fps. A route climbs a sculptural contour terrain and unfolds into an altitude profile. Terrain and figures are synthetic. This is an independent visual study, not client work or a real expedition.

[Watch](https://btusbefw.github.io/expedition-terrain-study/) · [MP4](https://btusbefw.github.io/expedition-terrain-study/terrain-study.mp4)

## Source and render

`composition.html` is the actual editable HTML/Three.js/SVG/GSAP source, with pinned Three.js 0.181.2 modules and MIT license in `vendor/`. GSAP is pinned to 3.14.2; HyperFrames to 0.8.174. It is not a native After Effects project.

In a separate scratch folder, copy composition.html to index.html, plus package.json and vendor/. Run `npm run check`, then `npx --yes hyperframes@0.8.174 render --quality delivery --fps 30 --output terrain-study.mp4`. Keep the publication index.html as the viewing page.

## Design

Fifteen irregular beveled geological layers, matte warm stone, low directional light, contact shadows and a slow 25-degree camera orbit. The orange route is a shadow-casting 3D tube whose path is sampled from the actual terrain surface by downward raycasts, with connectors over each ledge. The same layered sculpture and route morph continuously into a geological cross-section as the camera lowers. Three numerical SVG labels accompany the final section. Geometry is deterministic; no real-world map or client asset is used.

The fictional base is 2140 m, summit 5870 m, distance 8.4 km. The final profile maps altitude linearly and horizontal distance from the route’s cumulative 3D path length. Only the three relevant data labels remain. Independent-study disclosure stays beside the player.

## Verification

Full runtime/layout/motion/contrast check passed. One scene-structure lint warning is accepted for the short integrated canvas/SVG unit. H.264 output has 240 frames, 8.0 seconds, 1920 × 1080, 30 fps. Decoded one-second stills, transition frames and 320 × 180 thumbnail inspected.

CDRXRX · dev@dbrx.fr
