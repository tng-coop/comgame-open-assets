# comgame-open-assets

Open-standard 3D spatial assets (`ISO/IEC 12113` Khronos glTF 2.0 / `.glb`, Open Metaverse Interoperability `OMI_*`, and `VRMC_vrm-1.0`) for [tng.coop/comgame](https://tng.coop/comgame/) and [tng.coop/comgame/city-trial](https://tng.coop/comgame/city-trial/).

## Files

| File | Media Type | License | Standards & Contents |
| :--- | :--- | :--- | :--- |
| `world.glb` | `model/gltf-binary` | `CC0-1.0` | `glTF 2.0`, `OMI_physics_shape`, `OMI_physics_body`, `OMI_spawn_point`, `OMI_seat`, `OMI_link` |
| `world.gltf` | `model/gltf+json` | `CC0-1.0` | `glTF 2.0` JSON scene graph (`1.0 = 1m` SI meters, Right-Handed Y-Up) |
| `traffic-fleet.glb` | `model/gltf-binary` | `CC0-1.0` | `glTF 2.0` — 30 3D vehicle chassis + 200 cataloged vehicles (`Vehicle_001`..`Vehicle_200`: passenger, transit/bus/tram, commercial/freight/kei/tanker/mixer, municipal/utility/garbage/bucket/sweeper/loader, and police/ambulance/fire) derived from Kenney Car Kit 3.1, Kenney Train Kit, and TNG Co-op `CC0-1.0` meshes |
| `pedestrians.glb` | `model/gltf-binary` | `CC0-1.0` | `glTF 2.0` — 6-limb articulated pedestrian rig (`1.70m` SI height) + 16 pedestrian outfit palettes derived from Kenney Blocky Characters 2.0 (`CC0-1.0`) |
| `panasonic-xm1.glb` | `model/gltf-binary` | `CC0-1.0` | `glTF 2.0`, `OMI_physics_shape`, `OMI_physics_body`, `OMI_seat` |
| `yasu.vrm.glb` | `model/gltf-binary` | `CC-BY-4.0` | `glTF 2.0`, `VRMC_vrm-1.0` |
| `assets.manifest.json` | `application/json` | `CC0-1.0` | `SHA-256` & Subresource Integrity (`sri`) manifest |

## Immutable CDN Endpoints (`v0.3.0`)

- `https://cdn.jsdelivr.net/gh/tng-coop/comgame-open-assets@v0.3.0/world.glb`
- `https://cdn.jsdelivr.net/gh/tng-coop/comgame-open-assets@v0.3.0/traffic-fleet.glb`
- `https://cdn.jsdelivr.net/gh/tng-coop/comgame-open-assets@v0.3.0/pedestrians.glb`
- `https://cdn.jsdelivr.net/gh/tng-coop/comgame-open-assets@v0.3.0/panasonic-xm1.glb`
- `https://cdn.jsdelivr.net/gh/tng-coop/comgame-open-assets@v0.3.0/yasu.vrm.glb`
