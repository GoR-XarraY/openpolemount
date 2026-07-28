---
title: Cradle v2 — Risk Analysis
description: Risk analysis for the OpenPoleMount v2 universal holder — hazards, failure modes, and mitigations for a general-purpose 3D-printed IV-pole holder.
---

# Cradle v2 — Risk Analysis

This page assesses the risks specific to the **v2 universal holder**. It is a
passive, non-powered, 3D-printed part built on the OpenPoleMount mounting block.

!!! info "General-purpose hardware"
    The v2 holder is general-purpose mounting hardware — **not a medical device.**
    No electrical, chemical, or software function; no patient contact; no role in
    delivering or controlling therapy. The only hazard category is **mechanical**.
    See the [Safety & Disclaimer](../safety.md).

## Shared clamp risks

The v2 holder attaches with the same block-and-thumbscrew clamp as every
OpenPoleMount design. Those load-bearing hazards (slip, overload, thumbscrew
over-tightening, weak/mis-oriented print, material creep) and their mitigations are
covered once in the **[Mounting Block Risk Analysis](../mounting-block/risk-analysis.md)**
— read it alongside this page.

## Load rating

Recommended working load: **up to ~1.4 kg (3 lb)**, as a conservative starting
point at the recommended print settings. Verify safe support of your own load first.

## v2-specific hazards

| # | Hazard | Cause | Effect | Mitigation |
|---|---|---|---|---|
| 1 | Object rocks or shifts in the pocket | v2's pocket is **open and general-purpose**, not fitted to one object | Movement under load; object could tip out if loose | **Test-fit before relying on it.** There is no confirmed compatibility list. If loose, add padding/shim, reprint scaled, or use the form-fitting [v3](../iv-pole-v3/index.md). |
| 2 | Oversized object | Object larger than the pocket | Does not seat | Confirm your object fits the pocket envelope (~126 × 105 × 65 mm printed) before use. |
| 3 | Object falls when unclamped/handled | Open pocket does not capture the object | Drop during install/removal | Support the object by hand when placing or removing; do not rely on the pocket alone until seated and checked. |
| 4 | Cabling strain | Cable/tubing routed under tension | Pull on the mount or object | Route cabling with slack (see [Assembly](assembly.md)). |

## Evidence

The load-bearing clamp was validated in [destruction testing](../testing.md),
which was performed on the **v1/v2 body shape**: a deliberately under-spec print
never failed under normal load, the failure mode was safe and visible, and the
broken mount retained residual grip.

## Points of failure

| Point | Consequence | Detectability | Net risk |
|---|---|---|---|
| Block/thumbscrew clamp | See block analysis | Visible; residual grip | Low with correct install |
| Open pocket fit | Object rocks/tips if loose | Felt on test-fit and load test | Low–moderate; test-fit is essential |
| Print integrity | Weak part if settings/orientation wrong | Inspection + hand flex-test | Low with adherence to print guide |

---

*Informational only; not engineering certification or regulatory approval. See the
[Safety & Disclaimer](../safety.md).*
