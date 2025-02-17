# Better Vanilla Generator
[![](https://i.loli.net/2019/06/12/5d00613070e3947388.png)](http://www.mcbbs.net/thread-872584-1-1.html "更好的原生地形生成器")

Better vanilla generator plugin for Nukkit.

Warning: Please back up old worlds before using this plugin.

Please see [mcbbs](http://www.mcbbs.net/thread-872584-1-1.html) for more information.
## config.yml
```yaml
replace:
  # Whether to replace the overworld generator
  overworld: true
  # Whether to replace the nether generator
  nether: true

# Advanced configuration for generator
generator:
  general:
    sea_level: 64
  overworld:
    coordinate-scale: 684.412
    height:
      scale: 684.412
      noise-scale:
        x: 200.0
        z: 200.0
    detail:
      noise-scale:
        x: 80.0
        y: 160.0
        z: 80.0
    surface-scale: 0.0625
    base-size: 8.5
    stretch-y: 12.0
    biome:
      height-offset: 0.0
      height-weight: 1.0
      scale-offset: 0.0
      scale-weight: 1.0
      height:
        default: 0.1
        flat-shore: 0.0
        high-plateau: 1.5
        flatlands: 0.125
        swampland: -0.2
        mid-plains: 0.2
        flatlands-hills: 0.275
        swampland-hills: -0.1
        low-hills: 0.2
        hills: 0.45
        mid-hills2: 0.1
        default-hills: 0.2
        mid-hills: 0.3
        big-hills: 0.525
        big-hills2: 0.55
        extreme-hills: 1.0
        rocky-shore: 0.1
        low-spikes: 0.4125
        high-spikes: 1.1
        river: -0.5
        ocean: -1.0
        deep-ocean: -1.8
      scale:
        default: 0.2
        flat-shore: 0.025
        high-plateau: 0.025
        flatlands: 0.05
        swampland: 0.1
        mid-plains: 0.2
        flatlands-hills: 0.25
        swampland-hills: 0.3
        low-hills: 0.3
        hills: 0.3
        mid-hills2: 0.4
        default-hills: 0.4
        mid-hills: 0.4
        big-hills: 0.55
        big-hills2: 0.5
        extreme-hills: 0.5
        rocky-shore: 0.8
        low-spikes: 1.325
        high-spikes: 1.3125
        river: 0.0
        ocean: 0.1
        deep-ocean: 0.1
    density:
      fill:
        mode: 0
        sea-mode: 0
        offset: 0.0
  nether:
    coordinate-scale: 684.412
    height:
      scale: 2053.236
      noise-scale:
        x: 100.0
        z: 100.0
    detail:
      noise-scale:
        x: 80.0
        y: 60.0
        z: 80.0
    surface-scale: 0.0625
```
