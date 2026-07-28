---
title: v1 Accessory Box — Risk Analysis
description: Risk analysis for the OpenPoleMount v1 accessory box — hazards, failure modes, and mitigations for a pole-mounted 3D-printed storage box.
---

# v1 Accessory Box — Risk Analysis

This page assesses the risks specific to the **v1 accessory box**. It is a passive,
non-powered, 3D-printed storage box built on the OpenPoleMount mounting block.

!!! info "General-purpose hardware — no medical function"
    The v1 accessory box is general-purpose mounting hardware with **no medical
    function** — it holds small personal items and supplies. It is **not a medical
    device.** The only hazard category is **mechanical**. See the
    [Safety & Disclaimer](safety.md).

## Shared clamp risks

The v1 box attaches with the same block-and-thumbscrew clamp as every OpenPoleMount
design. Those load-bearing hazards (slip, overload, thumbscrew over-tightening,
weak/mis-oriented print, material creep) and their mitigations are covered once in
the **[Mounting Block Risk Analysis](mounting-block/risk-analysis.md)** — read it
alongside this page.

## Load rating

Recommended working load: **up to ~1.4 kg (3 lb)** of contents, as a conservative
starting point at the recommended print settings. Do not overfill.

## v1-specific hazards

| # | Hazard | Cause | Effect | Mitigation |
|---|---|---|---|---|
| 1 | Contents fall out | Box overfilled or tilted; loose small items | Items drop to the floor | Keep contents within the box; don't overfill above the rim; store small loose items in a bag inside the box. |
| 2 | Overloaded box | Contents heavier than the load rating | Box or clamp strain over time | Stay within ~1.4 kg of contents; use PETG for heavier or sustained loads. |
| 3 | Used as a device cradle | Mistaking the box for an equipment cradle | A seated device's front face is not accessible in the v1 pocket | Use v1 **only as a storage box**; for holding a device with its controls accessible, use [v3](iv-pole-v3/index.md) or [v2](iv-pole-v2/index.md). |
| 4 | Snag/knock | Box protrudes from the pole | Bumped in a walkway | Mount below the cradle and clear of walkways; keep the pole base stable. |

## Evidence

The load-bearing clamp was validated in [destruction testing](testing.md), which
was performed on the **v1/v2 body shape**: a deliberately under-spec print never
failed under normal load, the failure mode was safe and visible, and the broken
mount retained residual grip.

## Points of failure

| Point | Consequence | Detectability | Net risk |
|---|---|---|---|
| Block/thumbscrew clamp | See block analysis | Visible; residual grip | Low with correct install |
| Box contents | Items fall if overfilled/tilted | Visible | Low with sensible loading |
| Print integrity | Weak part if settings/orientation wrong | Inspection + hand flex-test | Low with adherence to print guide |

---

*Informational only; not engineering certification or regulatory approval. See the
[Safety & Disclaimer](safety.md).*
