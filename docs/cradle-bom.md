---
title: Cradle Bill of Materials (v1 / v2 / v3)
description: Bill of materials for the OpenPoleMount IV-pole cradles — fully 3D-printed, with measured filament use for each version.
---

# Cradle Bill of Materials — v1, v2, v3

Every OpenPoleMount cradle is **fully 3D-printed**: a cradle body plus the shared
printed T-handle thumbscrew. There are no proprietary or purchased parts — the only
consumable is filament. Each cradle is built on the certified
[OpenPoleMount mounting block](mounting-block/index.md) and clamps to a standard
IV pole the same way.

!!! info "General-purpose hardware"
    These are general-purpose mounting hardware, not medical devices. See the
    [Safety & Disclaimer](safety.md).

## Shared part — thumbscrew

| Part | File | Qty | Filament (measured) |
|---|---|---|---|
| T-handle Thumbscrew | [`thumbscrew_v14_flat_Thandle.stl`](https://github.com/GoR-XarraY/openpolemount/raw/main/stl/thumbscrew_v14_flat_Thandle.stl) | 1 | ~14 g (~11 cm³) |

All three cradles use this same thumbscrew.

## v3 — form-fitting cradle (current)

| Item | Value |
|---|---|
| Cradle file | [`OpenPoleMount_IV-Pole_v3.stl`](https://github.com/GoR-XarraY/openpolemount/raw/main/stl/OpenPoleMount_IV-Pole_v3.stl) |
| Printed size (L × W × H) | 125 × 100 × 66 mm |
| Filament, cradle body | **~109 g** PLA (~88 cm³) · **~91 g** PETG (~74 cm³) |
| + thumbscrew | ~14 g |
| Print time | ~3 h 10 m (PLA, 0.2 mm) |

## v2 — universal holder (available now)

| Item | Value |
|---|---|
| Cradle file | [`OpenPoleMount_IV-Pole_v2.stl`](https://github.com/GoR-XarraY/openpolemount/raw/main/stl/OpenPoleMount_IV-Pole_v2.stl) |
| Printed size (L × W × H) | 126 × 105 × 65 mm |
| Filament, cradle body | **~197 g** PLA (~159 cm³) |
| + thumbscrew | ~14 g |
| Print time | ~6–8 h (PLA, 0.2 mm) |

## v1 — accessory box (legacy)

| Item | Value |
|---|---|
| Body file | [`OpenPoleMount_IV-Pole_v1.stl`](https://github.com/GoR-XarraY/openpolemount/raw/main/stl/OpenPoleMount_IV-Pole_v1.stl) |
| Printed size (L × W × H) | 126 × 105 × 65 mm |
| Filament, body | **~206 g** PLA (~166 cm³) |
| + thumbscrew | ~14 g |
| Print time | ~6.5 h (PLA, 0.2 mm) |

## Consumable — filament

| Material | Spec | Notes |
|---|---|---|
| PLA (validated) or PETG | 1.75 mm, any reputable brand | No specific brand required. PETG is recommended for higher-stress or warmer environments; it uses near-identical volume, so mass differs only slightly with density (PLA ~1.24, PETG ~1.23–1.27 g/cm³). |

Filament figures above are measured from real single-unit slices at the recommended
0.2 mm settings; your slicer reports the exact figure for your setup.

## Print specification (safety-critical)

All cradles print at or above the shared recommended minimums:

| Parameter | Recommended minimum |
|---|---|
| Material | PLA (or PETG) |
| Layer height | 0.2 mm |
| Walls | 6 |
| Top/bottom | 2 mm |
| Infill | ≥35 %, 3D honeycomb (non-concentric — **not** lines/grid) |
| Supports | None required |
| Orientation | Cradle: pole channel vertical (layers perpendicular to clamp load). Thumbscrew: flat, handle face down. |

Full details: [v3 Print Guide](iv-pole-v3/print-settings.md) ·
[v2 Print Guide](iv-pole-v2/print-settings.md) · [About v1](print-settings.md).

## Source files

Editable source CAD (Blender `*.blend`) lives in the
[repository](https://github.com/GoR-XarraY/openpolemount) under `stl/`, available
for remixing under the hardware license (CERN-OHL-W-2.0).

---

*Fully 3D-printed — no BOM entries for purchased hardware. Provided for informational
purposes only; verify every printed part before use.*
