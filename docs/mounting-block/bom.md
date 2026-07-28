---
title: Mounting Block — Bill of Materials
description: Bill of materials for the OpenPoleMount mounting block — a fully 3D-printed pole clamp with no proprietary or non-printed parts.
---

# Mounting Block — Bill of Materials (BOM)

The OpenPoleMount mounting block is **fully 3D-printed**. There are no proprietary,
purchased, or non-printed components — the complete assembly is two printed parts
plus filament. This keeps the whole part openly reproducible by anyone with a
printer.

!!! info "General-purpose hardware"
    This is general-purpose mounting hardware, not a medical device. See the
    [Safety & Disclaimer](../safety.md) page.

## Printed parts

| # | Part | File | Qty | Manufacturer / Part No. |
|---|---|---|---|---|
| 1 | Pole Mounting Block | [`OpenPoleMount_Pole_Mounting_Block_V1.stl`](https://github.com/GoR-XarraY/openpolemount/raw/main/stl/OpenPoleMount_Pole_Mounting_Block_V1.stl) | 1 | Self-printed (open design — no proprietary part) |
| 2 | T-handle Thumbscrew | [`OpenPoleMount_Pole_Mounting_Block_ThandleThumbscrew-V1.stl`](https://github.com/GoR-XarraY/openpolemount/raw/main/stl/OpenPoleMount_Pole_Mounting_Block_ThandleThumbscrew-V1.stl) | 1 | Self-printed (open design — no proprietary part) |

## Consumable — filament

| Material | Spec | Notes |
|---|---|---|
| **PLA** (validated) or **PETG** (stronger, lighter, more heat/creep tolerant) | 1.75 mm filament, any reputable brand | No specific brand required. Destruction testing was performed in standard PLA; PETG is recommended for higher-stress or warmer environments. |

**Measured filament use** (single unit, sliced at 0.2 mm layer height on the
recommended profile):

| Part | Filament (measured) | Volume |
|---|---|---|
| T-handle Thumbscrew | **~14 g** | ~11 cm³ |
| Full v3 cradle (block + pocket) — *reference* | **~109 g** PLA | ~88 cm³ |

PLA and PETG use near-identical filament *volume*; mass differs only slightly with
density (PLA ~1.24, PETG ~1.27 g/cm³).

!!! note "Bare-block-only figure pending"
    The full v3 cradle above is measured from a real slice (single unit, ~3 h 10 m
    print). The **bare mounting block on its own** has not been sliced separately —
    as a subset of the cradle it uses less than the full-cradle figure. *(Pending a
    block-only slice for an exact number; your slicer's estimate is authoritative.)*

## Print specification (safety-critical)

The block is a load-bearing part; wall count and infill are safety-critical. Print
both parts at or above the shared recommended minimums:

| Parameter | Recommended minimum |
|---|---|
| Material | PLA (or PETG) |
| Layer height | 0.2 mm |
| Walls | 6 |
| Top/bottom | 2 mm |
| Infill | ≥35 %, 3D honeycomb (non-concentric — **not** lines/grid) |
| Supports | None required |
| Orientation | Block: pole channel vertical (layers perpendicular to clamp load). Thumbscrew: flat, handle face down. |

Full details and rationale: **[Print Guide](../iv-pole-v3/print-settings.md)**.

## Dimensions

Measured directly from the STL geometry:

| Part | Bounding size (X × Y × Z) |
|---|---|
| Pole Mounting Block v1 | 48.0 × 57.9 × 59.5 mm |
| T-handle Thumbscrew v1 | 102.0 × 53.0 × 16.0 mm |

## Source files

Editable source CAD (Blender `*.blend`) for both parts lives in the
[repository](https://github.com/GoR-XarraY/openpolemount) under `stl/`, available
for remixing under the hardware license (CERN-OHL-W-2.0).

---

*Fully 3D-printed — no BOM entries for purchased hardware. This documentation is
provided for informational purposes only; verify every printed part before use.*
