# Crownforge Terrain FINAL — 13 Sites / 200×200

This package is the reduced permanent-site terrain build for Crownforge: Kingdoms at War.

## Runtime contract
- Schema: v2
- Logical world: 200 × 200 tiles
- World pixels per tile: 44
- Native master: 8800 × 8800 px
- Terrain chunks: 4 × 4 = 16
- Chunk size: 2200 × 2200 px
- Royal: tile (103,98), world pixel (4532,4312)

## Permanent strategic hierarchy
- Royal: 1
- Mighty: 4
- Medium: 4
- Small: 4
- Total: 13

The former additional Medium/Small sites are not present in the strategic data or clearance mask. Buildings remain separate runtime objects.

## Terrain and gameplay validation
- Playable/traversable ratio: 78.13%
- Water ratio: 3.30%
- Obstacle ratio: 18.57%
- Chunk reconstruction max channel difference: 0
- Chunk reconstruction different pixels: 0
- Exact lossless reconstruction: True

All sixteen runtime chunks are direct lossless crops from the single completed master. `world_overview.webp` is downsampled from that master. Validation images are crops/downsamples of the completed terrain; only `strategic_sites_validation.png` contains validation markers.
