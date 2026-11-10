# TekGeo Semantic Layer Mapping Atlas — V1

This is the next production step after the layer-ready masters.

## Included
- Numbered reference SVG for M-01 and F-01
- PNG atlas previews with path numbers placed over the original artwork
- CSV inventory of each source path, its stable ID, fill color, path-data length and rendered bounds
- Byte-preserved original master SVGs

## How to use
1. Open the numbered atlas preview.
2. Match each number to a visual part of the character.
3. Record a semantic label only after checking the visible shape (for example `hair_back`, `face`, `shirt_front`, `left_forearm`, `tablet_screen`).
4. Keep the original path order where overlaps matter.
5. Only after mapping and review should paths be reorganized into semantic groups or used for animation.

## Important limitation
Numbers are source-path indices, not body-part labels. This package intentionally does not guess which path is an arm, face, shoe, etc. The numbered overlays are separate from the original vector artwork and can be removed.
