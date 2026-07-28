# v1 — Accessory Box (legacy)

!!! info "Use v2 to hold equipment. Use v1 as an accessory box."
    **v1 is the original print, and it's not functional as an equipment cradle** — the
    equipment's buttons and screen are not accessible when it is seated in v1. Use the current
    [**IV Pole Cradle v2**](iv-pole-v2/index.md). For a general-purpose pocket,
    **print v2**.

    v1 is still useful: it's best repurposed as an **accessory box that mounts on the
    pole below the cradle** — for alcohol wipes, spare caps, tubing, or other small supplies.
    The print settings, thumbscrew, and OpenPoleMount block are the same as v2, so it
    still clamps to any standard home IV pole.

The rest of this page is the original v1 print and assembly reference.

!!! danger "Safety Note — Read First"
    Anything you hang on an IV pole can fall. Print quality affects how well the box
    holds together and stays on the pole. The settings below are **minimums** — you are
    responsible for verifying mechanical integrity before use. See
    [Safety & Disclaimer](safety.md).

## Required Files

Download from [GitHub Releases](https://github.com/GoR-XarraY/openpolemount/releases/latest):

| File | Purpose | Quantity |
|---|---|---|
| `OpenPoleMount_IV-Pole_v1.stl` | IV pole cradle | 1 |
| `thumbscrew_v14_flat_Thandle.stl` | Thumbscrew for pole attachment | 1 |

!!! success "Tested to Destruction (2026-06-09)"
    An under-spec print (4-layer walls, 1 mm top/bottom, 15% non-structural infill, standard PLA)
    **never failed under load**. Failure only occurred under deliberate extreme over-tightening —
    the thumbscrew punched through the side wall, a safe and predictable failure mode.
    The recommended settings below are conservative relative to this tested limit.
    [See full testing results →](testing.md)

## Material

**PLA** is the tested and validated material for this design. Settings on this page
are based on PLA testing. Other materials (PETG, ASA, ABS) have not yet been tested —
if you print in another material, please share your results by
[opening an issue](https://github.com/GoR-XarraY/openpolemount/issues).

| Material | Status |
|---|---|
| **PLA** | ✅ Tested — use the settings below |
| PETG / ASA / ABS | ⚠️ Not yet tested — proceed at your own risk |
| TPU / Flexible | ❌ Not suitable — cannot support structural load |

## Recommended Print Settings (PLA, tested)

| Setting | Cradle | Thumbscrew |
|---|---|---|
| Layer height | 0.2 mm | 0.2 mm |
| **Wall count** | **1 mm minimum** | **1 mm minimum** |
| **Infill** | **25% minimum — non-concentric pattern** | **25% minimum** |
| Infill pattern | Non-concentric — **not** lines, grid, or concentric | same |
| Supports | None needed | Optional — single layer keeps part in place; brim works too |
| Print speed | 40–60 mm/s | 40–60 mm/s |

!!! danger "Wall and Infill Minimums Are Safety-Critical"
    Testing has shown that the mount **can crack if over-tightened** when walls
    or infill are below these minimums. The 1 mm walls + 25% non-concentric infill
    combination is the recommended minimum.

    **Do not use concentric, lines, or grid infill patterns** — they do not provide
    the same resistance to the stress concentration from the thumbscrew.

## Part Orientation

**Cradle:** Print with the pole channel vertical (mounting hole facing up). This
orients layer lines perpendicular to the primary load direction, maximizing
pull-out and shear strength.

**Thumbscrew:** Print flat with the T-handle face down. No supports needed.

## Support Settings

Neither part requires supports. Supports are optional on both:

- **Cradle:** supports are not required. If you use them, place under the cradle pocket. Tree or Normal both work; 45° threshold; 2–3 interface layers for clean removal.
- **Thumbscrew:** supports are not required. If enabled, the slicer typically places a single layer under the part — this helps hold it in place during printing. A brim works equally well for this purpose.

## Post-Processing

After printing:

1. Remove all supports carefully — use flush cutters, not a knife
2. Clean the thumbscrew threads with a brush if needed
3. Test-fit thumbscrew in the threaded hole — should turn smoothly by hand
4. Verify the pole channel diameter matches your IV pole
5. Check equipment fits snugly in the cradle pocket — should not rattle

## Verification Before Use

Run through this checklist before mounting any medical equipment:

- [ ] No visible layer delamination (check by pressing firmly — should not crack or flex excessively)
- [ ] No significant warping of the base or pole channel
- [ ] Thumbscrew threads cleanly with no binding or stringing
- [ ] Dry test: mount on pole without equipment, apply firm downward pressure — cradle must not slide
- [ ] Equipment seats fully without rocking or side-to-side movement

If any check fails, **do not use the part** — reprint with corrected settings.

!!! warning "Over-Tightening Risk"
    Once mounted, tighten the thumbscrew hand-tight plus one quarter-turn only.
    Over-tightening is the primary cause of cradle failure even in correctly
    printed parts. See the [Assembly Guide](assembly.md) for tightening instructions.
