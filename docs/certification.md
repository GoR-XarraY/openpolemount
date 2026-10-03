---
description: OpenPoleMount is certified open source hardware by the Open Source Hardware Association (OSHWA) — four certifications, US002834, US002862, US002863 and US002864.
---

# Certified Open Source Hardware

<div style="font-size:1.15rem;line-height:1.55;margin:0.5rem 0 1.5rem;">
OpenPoleMount is <strong>certified open source hardware</strong> by the
<a href="https://certification.oshwa.org/">Open Source Hardware Association (OSHWA)</a>.
Every cradle in the line — the v3 cradle, the v2 universal holder and the v1 accessory
box — is listed in OSHWA's public certification directory, each with its own ID.
</div>

<style>
  .opm-certs { display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:1.25rem; margin:1.5rem 0 2rem; }
  .opm-cert { border:1px solid var(--md-default-fg-color--lightest); border-radius:12px; padding:1rem; text-align:center; }
  .opm-cert__tile { display:block; background:#fff; border-radius:10px; padding:14px; margin-bottom:0.75rem; }
  .opm-cert__tile img { display:block; width:100%; max-width:170px; height:auto; margin:0 auto; }
  .opm-cert__name { font-weight:700; margin:0.25rem 0; }
  .opm-cert__meta { font-size:0.8rem; color:var(--md-default-fg-color--light); margin:0 0 0.5rem; }
</style>

<div class="opm-certs">
  <div class="opm-cert">
    <a class="opm-cert__tile" href="https://certification.oshwa.org/us002864.html" title="OSHWA certificate US002864">
      <img src="../images/oshwa/US002864-stacked.svg" alt="OSHW certification mark US002864" width="170" height="137"></a>
    <p class="opm-cert__name"><a href="../iv-pole-v3/">IV Pole Cradle v3</a></p>
    <p class="opm-cert__meta">US002864 · certified Oct 3, 2026<br>the current, recommended cradle</p>
  </div>
  <div class="opm-cert">
    <a class="opm-cert__tile" href="https://certification.oshwa.org/us002863.html" title="OSHWA certificate US002863">
      <img src="../images/oshwa/US002863-stacked.svg" alt="OSHW certification mark US002863" width="170" height="137"></a>
    <p class="opm-cert__name"><a href="../iv-pole-v2/">IV Pole Cradle v2 (Universal Holder)</a></p>
    <p class="opm-cert__meta">US002863 · certified Oct 3, 2026</p>
  </div>
  <div class="opm-cert">
    <a class="opm-cert__tile" href="https://certification.oshwa.org/us002862.html" title="OSHWA certificate US002862">
      <img src="../images/oshwa/US002862-stacked.svg" alt="OSHW certification mark US002862" width="170" height="137"></a>
    <p class="opm-cert__name"><a href="../print-settings/">IV Pole Accessory Box (v1)</a></p>
    <p class="opm-cert__meta">US002862 · certified Oct 3, 2026</p>
  </div>
  <div class="opm-cert">
    <a class="opm-cert__tile" href="https://certification.oshwa.org/us002834.html" title="OSHWA certificate US002834">
      <img src="../images/oshwa/US002834-stacked.svg" alt="OSHW certification mark US002834" width="170" height="137"></a>
    <p class="opm-cert__name"><a href="../iv-pole-v2/">IV Pole Cradle</a></p>
    <p class="opm-cert__meta">US002834 · certified Jul 10, 2026<br>the project's first certification</p>
  </div>
</div>

Click any mark to open its certificate in OSHWA's directory.

## What the certification means

OSHWA certification confirms that a project meets the
[Open Source Hardware Definition](https://www.oshwa.org/definition/): the design files,
documentation and bill of materials are public, and the licenses let anyone study,
make, modify and share the hardware. For OpenPoleMount that means:

- **Hardware:** [CERN-OHL-W-2.0](license.md) — print it, change it, sell it; improvements to the design itself stay open.
- **Documentation:** [CC-BY-SA-4.0](license.md).
- **Source files:** the native Blender `.blend` sources and print-ready STLs are in the
  [GitHub repository](https://github.com/GoR-XarraY/openpolemount) and on the
  [v3.0.0 release](https://github.com/GoR-XarraY/openpolemount/releases/tag/v3.0.0).

!!! warning "Open source — not a medical or safety certification"
    OSHWA certifies that the design is **open**. It does not test strength or safety,
    and it is not a medical certification. OpenPoleMount remains general-purpose
    mounting hardware, not a medical device, and is not FDA-cleared.
    See [Safety & Disclaimer](safety.md).

## Plain-text mark

Where an image can't be used, OSHWA's plain-text form is:

```
[OSHW] US002864 | Certified open source hardware | oshwa.org/cert
```
