# comgame-open-assets

Open-standard 3D spatial assets (`ISO/IEC 12113` Khronos glTF 2.0 / `.glb`, Open Metaverse Interoperability `OMI_*`, and `VRMC_vrm-1.0`) for [tng.coop/comgame](https://tng.coop/comgame/).

## Files

| File | Media Type | License | Standards |
| :--- | :--- | :--- | :--- |
| `world.glb` | `model/gltf-binary` | `CC0-1.0` | `glTF 2.0`, `OMI_physics_shape`, `OMI_physics_body`, `OMI_spawn_point`, `OMI_seat`, `OMI_link` |
| `world.gltf` | `model/gltf+json` | `CC0-1.0` | `glTF 2.0` JSON scene graph (`1.0 = 1m` SI meters, Right-Handed Y-Up) |
| `panasonic-xm1.glb` | `model/gltf-binary` | `CC0-1.0` | `glTF 2.0`, `OMI_physics_shape`, `OMI_physics_body`, `OMI_seat` |
| `yasu.vrm.glb` | `model/gltf-binary` | `CC-BY-4.0` | `glTF 2.0`, `VRMC_vrm-1.0` |
| `assets.manifest.json` | `application/json` | `CC0-1.0` | `SHA-256` & Subresource Integrity (`sri`) manifest |

## Immutable CDN Endpoints (`v0.1.0`)

- `https://cdn.jsdelivr.net/gh/tng-coop/comgame-open-assets@v0.1.0/world.glb`
- `https://cdn.jsdelivr.net/gh/tng-coop/comgame-open-assets@v0.1.0/panasonic-xm1.glb`
- `https://cdn.jsdelivr.net/gh/tng-coop/comgame-open-assets@v0.1.0/yasu.vrm.glb`
