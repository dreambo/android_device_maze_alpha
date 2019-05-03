# TWRP device tree for Maze Alpha

### Specifications

Component Type | Details
-------:|:-------------------------
CPU     | Octa-core 2.39GHz MT6757CD Mediatek Helio P25
GPU     | Mali-T880 MP2
Memory  | 6 GB RAM
Shipped Android Version | 	Android 7.0 Nougat
Storage | 64GB
Battery | 4080 mAh
Display | 5.99" 1080 x 2160 px DPI 403
Primary Camera | 21 MP + 2 MP,optical image stabilization, autofocus, dual LED flash
Secondary Camera | 13 MP

---

This device tree can be used to build twrp for Maze Alpha


## Build Instructions
```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_alpha-eng
mka recoveryimage
```
