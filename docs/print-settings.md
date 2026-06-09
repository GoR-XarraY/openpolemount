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

## Material Selection

| Material | Suitability | Notes |
|---|---|---|
| **PETG** | ✅ Minimum recommended | Good strength, easy to print, moisture-resistant |
| **ASA** | ✅ Best choice | UV and chemical resistant, better for humid environments |
| **ABS** | ✅ Good | Strong, but prone to warping during print |
| PLA | ⚠️ Not recommended | Lower impact strength, degrades in heat and humidity |
| TPU / Flexible | ❌ Not suitable | Cannot support structural load |

## Recommended Print Settings

| Setting | Cradle | Thumbscrew |
|---|---|---|
| Layer height | 0.2 mm | 0.2 mm |
| **Infill** | **≥40%** (gyroid or grid) | **≥40%** |
| Perimeters / walls | ≥4 | ≥4 |
| Top/bottom layers | ≥5 | ≥5 |
| Supports | Required (see below) | Not needed |
| Print speed | 40–60 mm/s | 40–60 mm/s |

!!! danger "Minimum Infill: 40%"
    Do not print load-bearing parts below 40% infill. This mount holds medical
    equipment over a patient. When in doubt, print denser.

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
