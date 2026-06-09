# Print Guide

!!! danger "Safety Note — Read First"
    This is a load-bearing mount. A Curlin CMS6000 pump with a full IV bag weighs
    approximately **1.4 kg (3 lbs)**. Print quality directly affects safety.
    The settings below are **minimums** — you are responsible for verifying
    mechanical integrity before use. See [Safety & Disclaimer](safety.md).

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
| **Wall thickness** | **2 mm minimum** | **2 mm minimum** |
| **Top/bottom thickness** | **2 mm minimum** | **2 mm minimum** |
| **Infill** | **15% minimum — 3D honeycomb (preferred) or other non-concentric pattern** | **15% minimum** |
| Infill pattern | 3D honeycomb (preferred), gyroid, or cubic — **not** lines, grid, or concentric | same |
| Supports | Required (see below) | Not needed |
| Print speed | 40–60 mm/s | 40–60 mm/s |

!!! danger "Wall and Infill Minimums Are Safety-Critical"
    Testing has shown that the mount **can crack if over-tightened** when walls
    or infill are below these minimums. The 2 mm wall + 2 mm top/bottom + 15%
    non-concentric infill combination was validated in initial testing.

    **Do not use concentric, lines, or grid infill patterns** — they do not provide
    the same resistance to the stress concentration from the thumbscrew.
    3D honeycomb is the preferred pattern.

## Part Orientation

**Cradle:** Print with the pole channel vertical (mounting hole facing up). This
orients layer lines perpendicular to the primary load direction, maximizing
pull-out and shear strength.

**Thumbscrew:** Print flat with the T-handle face down. No supports needed.

## Support Settings

The cradle requires supports under the pump cradle pocket:

- Support type: Tree or Normal (both work well)
- Support angle threshold: 45°
- Interface layers: 2–3 (makes clean removal easier)
- Support interface material: same as main material

## Post-Processing

After printing:

1. Remove all supports carefully — use flush cutters, not a knife
2. Clean the thumbscrew threads with a brush if needed
3. Test-fit thumbscrew in the threaded hole — should turn smoothly by hand
4. Verify the pole channel diameter matches your IV pole
5. Check pump fits snugly in the cradle pocket — should not rattle

## Verification Before Use

Run through this checklist before mounting any medical equipment:

- [ ] No visible layer delamination (check by pressing firmly — should not crack or flex excessively)
- [ ] No significant warping of the base or pole channel
- [ ] Thumbscrew threads cleanly with no binding or stringing
- [ ] Dry test: mount on pole without pump, apply firm downward pressure — cradle must not slide
- [ ] Pump seats fully without rocking or side-to-side movement

If any check fails, **do not use the part** — reprint with corrected settings.

!!! warning "Over-Tightening Risk"
    Once mounted, tighten the thumbscrew hand-tight plus one quarter-turn only.
    Over-tightening is the primary cause of cradle failure even in correctly
    printed parts. See the [Assembly Guide](assembly.md) for tightening instructions.
