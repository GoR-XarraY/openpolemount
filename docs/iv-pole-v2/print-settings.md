# Print Guide — IV Pole Mount v2 (Universal Device Holder)

!!! danger "Safety Note — Read First"
    This is a load-bearing mount, rated to approximately **1.4 kg (3 lbs)** as a
    general starting point — match your equipment's actual weight against this
    rating before use. Print quality directly affects safety. The settings below are
    **minimums** — you are responsible for verifying mechanical integrity, and
    device fit, before use. See [Safety & Disclaimer](../safety.md).

!!! info "Need a tighter, more form-fitting pocket? Print v3 instead"
    v2's pocket is a general-purpose shape, not fitted to one specific device.
    [**v3**](../iv-pole-v3/index.md) is the recommended, more form-fitting cradle.
    See the [v3 Print Guide](../iv-pole-v3/print-settings.md).

!!! info "V2 vs V1 — What's Different"
    The IV Pole Mount v2 has a **different exterior shape** compared to v1.
    All functional dimensions are identical — same pole channel, same general-purpose
    pocket, same thumbscrew thread. All print settings, material requirements, and
    specifications on this page are the same as v1. Choose whichever shape you prefer;
    they are functionally equivalent.

## Required Files

Download from [GitHub Releases](https://github.com/GoR-XarraY/openpolemount/releases/latest):

| File | Purpose | Quantity |
|---|---|---|
| `OpenPoleMount_IV-Pole_v2.stl` | IV pole cradle (v2 shape) | 1 |
| `thumbscrew_v14_flat_Thandle.stl` | Thumbscrew for pole attachment | 1 |

!!! success "Tested to Destruction (2026-06-09)"
    An under-spec print of the v1 body (4-layer walls, 1 mm top/bottom, 15% non-structural infill, standard PLA)
    **never failed under load**. Failure only occurred under deliberate extreme over-tightening —
    the thumbscrew punched through the side wall, a safe and predictable failure mode.
    The v2 body shares the same critical wall geometry and is expected to behave identically.
    The recommended settings below are conservative relative to this tested limit.
    [See full testing results →](../testing.md)

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
| **Wall count** | **1 mm minimum (≈2–3 perimeters at 0.4 mm nozzle)** | **1 mm minimum** |
| **Top/bottom thickness** | **2 mm minimum** | **2 mm minimum** |
| **Infill** | **25% minimum — 3D honeycomb (preferred) or other non-concentric pattern** | **25% minimum** |
| Infill pattern | 3D honeycomb (preferred), gyroid, or cubic — **not** lines, grid, or concentric | same |
| Supports | None needed | Optional — single layer keeps part in place; brim works too |
| Print speed | 40–60 mm/s | 40–60 mm/s |

!!! danger "Wall and Infill Minimums Are Safety-Critical"
    Testing has shown that the mount **can crack if over-tightened** when walls
    or infill are below these minimums. The 1 mm wall + 2 mm top/bottom + 25%
    non-concentric infill combination is the recommended minimum.

    **Do not use concentric, lines, or grid infill patterns** — they do not provide
    the same resistance to the stress concentration from the thumbscrew.
    3D honeycomb is the preferred pattern.

## Part Orientation

**Cradle:** Print with the pole channel vertical (mounting hole facing up). This
orients layer lines perpendicular to the primary load direction, maximizing
pull-out and shear strength.

**Thumbscrew:** Print flat with the T-handle face down. No supports needed.

## Support Settings

Neither part requires supports. Supports are optional on both:

- **Cradle:** supports are not required. If you use them, place under the device cradle pocket. Tree or Normal both work; 45° threshold; 2–3 interface layers for clean removal.
- **Thumbscrew:** supports are not required. If enabled, the slicer typically places a single layer under the part — this helps hold it in place during printing. A brim works equally well for this purpose.

## Printing Footage

<div style="display:flex;justify-content:center;margin:1.5rem 0;">
  <iframe width="315" height="560"
    src="https://www.youtube.com/embed/z05xgJhH_BQ"
    title="OpenPoleMount IV Pole V2 — printing the first one"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

## Post-Processing

After printing:

1. Remove all supports carefully — use flush cutters, not a knife
2. Clean the thumbscrew threads with a brush if needed
3. Test-fit thumbscrew in the threaded hole — should turn smoothly by hand
4. Verify the pole channel diameter matches your IV pole
5. Check device fits snugly in the cradle pocket — should not rattle

## Verification Before Use

Run through this checklist before mounting any equipment:

- [ ] No visible layer delamination (check by pressing firmly — should not crack or flex excessively)
- [ ] No significant warping of the base or pole channel
- [ ] Thumbscrew threads cleanly with no binding or stringing
- [ ] Dry test: mount on pole without a device, apply firm downward pressure — cradle must not slide
- [ ] Device seats fully without rocking or side-to-side movement

If any check fails, **do not use the part** — reprint with corrected settings.

!!! warning "Over-Tightening Risk"
    Once mounted, tighten the thumbscrew hand-tight plus one quarter-turn only.
    Over-tightening is the primary cause of cradle failure even in correctly
    printed parts. See the [Assembly Guide](assembly.md) for tightening instructions.
