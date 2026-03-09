# RAID Visualizer

An interactive, educational RAID level visualizer. Open `index.html` directly in any browser — no server, no build step, no dependencies.

## What it does

- Visualizes block distribution across drives for RAID 0, 1, 5, 6, and 10
- Shows usable capacity, space efficiency, fault tolerance, and read/write performance
- Updates in real time as you adjust drive count and size
- Includes a fail mode to simulate drive failures and see degraded/failed array states
- Dark and light theme, with preference saved across sessions

## Usage

```
open index.html
```

Adjust the sliders and RAID level buttons to explore how each configuration affects capacity and redundancy. Enable **Fail Mode** and click individual drives to simulate failures.

## Presets

| Name | Config | Use case |
|------|--------|----------|
| NAS 4-bay | 4 × 4 TB, RAID 5 | Home NAS |
| Home Media | 4 × 8 TB, RAID 5 | Plex server |
| Enterprise 8 | 8 × 12 TB, RAID 6 | High-availability storage |
| Max Speed | 4 × 2 TB, RAID 0 | Performance scratch disk |
| Max Fault | 6 × 8 TB, RAID 10 | Maximum redundancy |

## Notes

Block layouts are conceptual representations of stripe distribution, not exact byte-level mappings.
