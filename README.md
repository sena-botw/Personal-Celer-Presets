# Personal-Celer-Presets
Celer presets for personal use

## Example
Example of `project.yaml`
```yaml
# project.yaml
title: Route Name
version: 1.0.0
route:
  use: ./main.yaml
config:
  - use: Pistonight/celer-presets/botw/map.yaml
  - use: sena-botw/Personal-Celer-Presets/full.yaml
  - plugins:
    - use: link      # optional
    - use: variables # required
      with:
        init:
          # Uncomment the following three lines labeled “With DLC” or “Without DLC”
          # With DLC
          #with-dlc: 1
          #great-plateau-count: 2
          #map-pct-items-total: 1227

          # Without DLC
          #with-dlc: 0
          #great-plateau-count: 1
          #map-pct-items-total: 1209
```
