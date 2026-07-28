---
title: Cradle v3 — Risk Analysis
description: Risk analysis for the OpenPoleMount v3 cradle — hazards, failure modes, and mitigations for a form-fitting 3D-printed IV-pole cradle.
---

# Cradle v3 — Risk Analysis

This page assesses the risks specific to the **v3 cradle**. It is a passive,
non-powered, 3D-printed part built on the OpenPoleMount mounting block.

!!! info "General-purpose hardware"
    The v3 cradle is general-purpose mounting hardware — **not a medical device.**
    No electrical, chemical, or software function; no patient contact; no role in
    delivering or controlling therapy. The only hazard category is **mechanical**.
    See the [Safety & Disclaimer](../safety.md).

## Shared clamp risks

The v3 cradle attaches with the same block-and-thumbscrew clamp as every
OpenPoleMount design. Those load-bearing hazards (slip, overload, thumbscrew
over-tightening, weak/mis-oriented print, material creep) and their mitigations are
covered once in the **[Mounting Block Risk Analysis](../mounting-block/risk-analysis.md)**
— read it alongside this page.

## Load rating

Recommended working load: **up to ~1.4 kg (3 lb)**, as a conservative starting
point at the recommended print settings. Verify safe support of your own load first.

## v3-specific hazards

| # | Hazard | Cause | Effect | Mitigation |
|---|---|---|---|---|
| 1 | Object does not seat fully | Object larger than the form-fitting pocket | Poor seating; object sits high or proud | v3's pocket is sized to a compact envelope (~124 × 99 × 65 mm). Check your object fits before relying on it; use [v2](../iv-pole-v2/index.md) for a more open pocket, or resize the model. |
| 2 | Object rocks in the pocket | Object smaller than the pocket | Movement under load | The form-fitting v3 pocket minimises this vs. an open holder, but confirm a snug fit; add a shim or reprint scaled if loose. |
| 3 | Front face obstructed | Object oriented wrong way in the pocket | Controls/screen not reachable | Seat the object with its front face outward — the v3 pocket is shaped to keep the front accessible. |
| 4 | Cabling strain | Cable/tubing routed under tension | Pull on the mount or the object | Route cabling with slack so it exits without tension (see [Assembly](assembly.md)). |

## Evidence

The load-bearing clamp shared by v3 was validated in
[destruction testing](../testing.md): a deliberately under-spec print never failed
under normal load, the failure mode was safe and visible, and the broken mount
retained residual grip. The v3 body reuses that same clamp geometry; its
form-fitting pocket has not been separately tested to failure.

## Points of failure

| Point | Consequence | Detectability | Net risk |
|---|---|---|---|
| Block/thumbscrew clamp | See block analysis | Visible; residual grip | Low with correct install |
| Pocket fit | Object rocks or sits proud if mismatched | Felt on test-fit and load test | Low with correct-size object |
| Print integrity | Weak part if settings/orientation wrong | Inspection + hand flex-test | Low with adherence to print guide |

---

*Informational only; not engineering certification or regulatory approval. See the
[Safety & Disclaimer](../safety.md).*
