---
title: Mounting Block — Risk Analysis
description: Risk analysis for the OpenPoleMount mounting block — hazards, failure modes, and mitigations for a 3D-printed pole clamp.
---

# Mounting Block — Risk Analysis

This page estimates and assesses the risks of the OpenPoleMount mounting block, its
failure modes, and how they are mitigated. It follows the spirit of a lightweight
ISO 14971-style analysis, scaled to what the part actually is: a **passive,
non-powered, 3D-printed pole clamp**.

!!! info "Scope & nature of the part"
    OpenPoleMount is **general-purpose mounting hardware — not a medical device.**
    It has no electrical, chemical, or software function, no patient contact, and
    no role in delivering, controlling, or supporting medication or therapy. The
    single hazard category is **mechanical**: the secure retention of whatever is
    mounted on a pole. See the [Safety & Disclaimer](../safety.md).

## Summary of residual risk

The dominant risk is a mounted object shifting or falling if the mount is
mis-printed, overloaded, or mis-installed. This is mitigated by conservative,
documented print settings; a stated load rating; a simple installation procedure;
and — demonstrated by [destruction testing](../testing.md) — a **safe, visible,
non-catastrophic failure mode that retains residual grip** rather than releasing
suddenly. With the recommended settings and correct installation, residual risk is
low for the intended general pole-mounting use.

## Load rating

Recommended working load: **up to ~1.4 kg (3 lb)** per mount, as a conservative
starting point at the recommended print settings. Actual capacity depends on
material, print quality, and pole fit — verify safe support of your own load before
relying on it.

## Hazard / risk table

| # | Hazard | Cause | Potential effect | Mitigation |
|---|---|---|---|---|
| 1 | Mount slips or rotates on the pole | Thumbscrew under-tightened; pole diameter outside the channel's range; dusty/greasy pole | Mounted object shifts or drops | Hand-tighten + ¼ turn; match the pole diameter (resize the model if needed); clean the pole. Grip is by printed channel geometry, not just friction. |
| 2 | Overload | Object heavier than the ~1.4 kg rating; shock/jerk loads | Part deformation or failure | Respect the stated load rating; avoid impact loads; use PETG and/or higher infill for heavier objects. |
| 3 | Thumbscrew over-tightened to failure | Sustained force far beyond hand-tight | Crack propagates and the thumbscrew punches through the side wall | **Do not over-tighten** (documented in the [Assembly Guide](../iv-pole-v3/assembly.md)). Testing shows this requires force no normal user applies, the pole channel stays intact, failure is **immediately visible**, and the broken mount **retains residual grip**. |
| 4 | Weak print | Wrong infill pattern (lines/grid instead of 3D honeycomb), too few walls, under-extrusion, layer delamination | Reduced strength; premature failure under load | Follow the [Print Guide](../iv-pole-v3/print-settings.md) minimums (≥1 mm walls, 2 mm top/bottom, ≥25 % 3D honeycomb); inspect each print; flex-test by hand before use. |
| 5 | Wrong print orientation | Block printed with layers parallel to the clamp load | Layer-line splitting under clamping force | Print the block with the pole channel **vertical** (layers perpendicular to load), thumbscrew flat — per the print guide. |
| 6 | Material creep / heat softening | PLA under sustained load, or in a warm environment (PLA softens ~60 °C) | Slow deformation / loss of grip over time | Use **PETG** for sustained-load or warm conditions; inspect periodically; do not place near heat sources; re-check tightness. |
| 7 | Pole damage | Excessive clamping torque | Marring of the pole | The printed clamp face is far gentler than metal hardware by design; use only the specified torque. This is a **reduced** risk versus metal clamps. |
| 8 | Undetected degradation | UV exposure, repeated stress cycles, ageing filament | Gradual weakening | Failure mode is visible, not hidden (see testing); inspect before each use; reprint if cracked, warped, or flexing. |

## Evidence: destruction testing

A deliberately **under-spec** print (below recommended minimums) was tested to
destruction on 2026-06-09. Key results:

- It **never failed under normal load** — the failure point was only reached under
  extreme, sustained thumbscrew over-tightening far beyond any real use.
- Failure was **localised** to the thumbscrew side wall; the pole channel and body
  stayed intact.
- The failure was **immediately visible** — no hidden or gradual weakening.
- The broken mount **still held on the pole** (residual grip) — a mounted object
  would not suddenly drop; there is time to notice and act.

The recommended settings are ~2× the wall thickness of that worst-case test print,
giving a generous margin. Full write-up and video: **[Strength Testing](../testing.md)**.

## Mitigation & maintenance summary

- Print at or above the recommended minimums, in the correct orientation.
- Inspect each printed part; reject any with cracks, warping, delamination, or flex.
- Match (or resize to) your pole diameter.
- Hand-tighten plus a quarter turn — **do not over-tighten**.
- Stay within the ~1.4 kg load rating; use PETG for heavier or warmer use.
- Re-inspect and re-check tightness periodically; reprint if any damage appears.

## Points of failure (single-point summary)

| Point of failure | Consequence | Detectability | Net risk |
|---|---|---|---|
| Thumbscrew side wall | Localised crack under gross over-tightening | Immediately visible; residual grip retained | Low |
| Pole channel grip | Slip if under-tightened or wrong pole size | Visible/felt on install and load test | Low with correct install |
| Print integrity | Weak part if settings/orientation wrong | Detectable by inspection and hand flex-test | Low with adherence to guide |

---

*This analysis is provided for informational purposes only and does not constitute
engineering certification or regulatory approval. See the
[Safety & Disclaimer](../safety.md).*
