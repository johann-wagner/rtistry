# rtistry

**Author:** Johann Wagner  
**Date:** 2025-10-18  

## Overview
This project explores generative art using R and the **tidyverse** ecosystem. It is inspired by and modified from [Thinking Outside the Grid](https://thetidytrekker.com/post/thinkingpatterns) by [Meghan Harris](https://thetidytrekker.com/post/thinking-outside-the-grid/thinking-outside-the-grid.html).

## Features
- **Single Point Plot:** Demonstrates minimal ggplot structure.
- **Random Lines:** Generates randomised line segments converging to a central point.
- **Geometric Shapes:** Creates polygons (e.g., squares) and combines them with random lines.
- **Colour Variations:** Applies palettes from **RColorBrewer** for aesthetic diversity.
- **Radial and Polar Coordinates:** Transforms Cartesian plots into circular layouts.
- **Density-Based Art:** Uses `geom_density2d_filled` for layered, planet-like visuals.

## Dependencies
Ensure the following packages are installed:
- `tidyverse`
- `RColorBrewer`
- `cowplot`
- `patchwork`

Install missing packages with:
```r
install.packages(c("tidyverse", "RColorBrewer", "cowplot", "patchwork"))
```

