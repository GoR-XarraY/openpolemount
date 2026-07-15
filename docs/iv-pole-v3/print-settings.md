# Print Guide — IV Pole Mount v3

!!! danger "Safety Note — Read First"
    This is a load-bearing mount. A Curlin CMS6000 pump with a full IV bag weighs
    approximately **1.4 kg (3 lbs)**. Print quality directly affects safety.
    The settings below are **minimums** — you are responsible for verifying
    mechanical integrity before use. See [Safety & Disclaimer](../safety.md).

!!! warning "STL Files Not Yet Published — Coming Shortly"
    The v3 print files are still being finalized for public release. The working
    export files currently in the repository (`stl/OpenPoleMount_IV-Pole_v3_textured1.stl`
    and `stl/OpenPoleMount_IV-Pole_v3_watertight.bumpmesh`) are **not** in the same
    print-ready format used for the v1/v2 releases and should not be printed from
    directly. Once a finalized `OpenPoleMount_IV-Pole_v3.stl` is published to
    [GitHub Releases](https://github.com/GoR-XarraY/openpolemount/releases/latest),
    this page will be updated with the download link.

    Want to print something today? [**v2**](../iv-pole-v2/print-settings.md) is
    fully released and print-ready now.

!!! info "V3 vs V2 — What's Different"
    IV Pole Mount v3 uses a **smaller, more form-fitting pocket** shaped specifically
    around the Curlin CMS6000, redesigned from feedback on v2's more open pocket.
    The pole channel and thumbscrew interface are unchanged. **Print settings below
    carry over the same conservative minimums validated for v1/v2** — the v3 pocket
    itself has not yet been separately destruction-tested. Treat these as a starting
    point, not a substitute for your own inspection before use.

## Required Files *(coming shortly)*

| File | Purpose | Quantity |
|---|---|---|
| `OpenPoleMount_IV-Pole_v3.stl` *(pending release)* | IV pole cradle (v3 shape) | 1 |
| `thumbscrew_v14_flat_Thandle.stl` | Thumbscrew for pole attachment (same part as v1/v2) | 1 |

!!! info "Testing Status — Pending"
    The [destruction testing](../testing.md) on file was performed on the v1/v2
    cradle body shape. **v3 has not yet been separately tested to failure.** The
    settings below are carried over from that testing as a conservative starting
    point because the pole channel, thumbscrew boss, and wall construction method
    are shared across all three versions — but this has not been independently
    confirmed for the v3 pocket geometry specifically. *(Pending George's
    confirmation/testing before this note can be upgraded to a tested claim.)*

## Material

**PLA** is the tested and validated material for this design family. Settings on
this page are based on PLA testing of v1/v2. Other materials (PETG, ASA, ABS) have
not yet been tested — if you print in another material, please share your results
by [opening an issue](https://github.com/GoR-XarraY/openpolemount/issues).

| Material | Status |
|---|---|
| **PLA** | ✅ Tested (v1/v2 geometry) — use the settings below |
| PETG / ASA / ABS | ⚠️ Not yet tested — proceed at your own risk |
| TPU / Flexible | ❌ Not suitable — cannot support structural load |

## Recommended Print Settings (PLA, carried over from v1/v2 testing)

| Setting | Cradle | Thumbscrew |
|---|---|---|
| Layer height | 0.2 mm | 0.2 mm |
| **Wall count** | **6 walls (≈2.4 mm at 0.4 mm nozzle)** | **6 walls** |
| **Top/bottom thickness** | **2 mm minimum** | **2 mm minimum** |
| **Infill** | **35% minimum — 3D honeycomb (preferred) or other non-concentric pattern** | **35% minimum** |
| Infill pattern | 3D honeycomb (preferred), gyroid, or cubic — **not** lines, grid, or concentric | same |
| Supports | None needed | Optional — single layer keeps part in place; brim works too |
| Print speed | 40–60 mm/s | 40–60 mm/s |

!!! danger "Wall and Infill Minimums Are Safety-Critical"
    Testing on the v1/v2 shape has shown that the mount **can crack if
    over-tightened** when walls or infill are below these minimums. The 6-wall +
    2 mm top/bottom + 35% non-concentric infill combination is the recommended
    minimum until v3-specific testing is complete.

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

- **Cradle:** supports are not required. If you use them, place under the pump cradle pocket. Tree or Normal both work; 45° threshold; 2–3 interface layers for clean removal.
- **Thumbscrew:** supports are not required. If enabled, the slicer typically places a single layer under the part — this helps hold it in place during printing. A brim works equally well for this purpose.

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
- [ ] Pump seats fully without rocking or side-to-side movement — **pending George's own
      physical fit-test report on the finished v3 print; the photos on the
      [overview page](index.md) show a successful hand-fit but have not been logged
      as a formal verification pass**

If any check fails, **do not use the part** — reprint with corrected settings.

!!! warning "Over-Tightening Risk"
    Once mounted, tighten the thumbscrew hand-tight plus one quarter-turn only.
    Over-tightening is the primary cause of cradle failure even in correctly
    printed parts. See the [Assembly Guide](assembly.md) for tightening instructions.
