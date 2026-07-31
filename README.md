# OpenPoleMount

[![License: CERN-OHL-W-2.0](https://img.shields.io/badge/Hardware-CERN--OHL--W--2.0-blue)](LICENSE)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/Docs-CC--BY--SA--4.0-lightgrey)](LICENSE-docs)
[![Website](https://img.shields.io/badge/Website-openpolemount.com-teal)](https://openpolemount.com)

**An open-source, 3D-printable universal equipment cradle — and an open mounting standard for home IV poles.**

> **This is not a business — it's an open-source hardware project.** Every file is
> free. The goal is that anyone who needs a cradle can print one themselves. A
> print-on-demand option exists only so people without a printer aren't left out,
> at cost.

> ⚠️ **NOT A MEDICAL DEVICE — REFERENCE DESIGN ONLY.** OpenPoleMount is
> general-purpose mounting hardware provided for informational and educational
> purposes. It is **not** intended to deliver, control, or support medication or
> therapy, and it has **not** been evaluated or cleared by the FDA or any
> regulatory body. See [DISCLAIMER.md](DISCLAIMER.md) before use.

---

## What It Is

OpenPoleMount is a printed cradle that clamps to a standard home IV pole to hold
equipment. The mounting section — the **OpenPoleMount block** — is an open
standard, so any community-designed accessory can attach to any compatible home
IV pole.

The project began when a home-care caregiver couldn't source a mounting cradle
and printed their own. The files are shared freely so others can do the same.

## Versions

**v3 — current, recommended.** A smaller, more form-fitting cradle refined from
user feedback, built around the OpenPoleMount block standard. The cradle holds
equipment on the pole with the front face accessible, and a printed T-handle
thumbscrew clamps it to a standard home IV pole.

> v3's print files are now available — download the
> [v3 STL](https://github.com/GoR-XarraY/openpolemount/raw/main/stl/OpenPoleMount_IV-Pole_v3.stl)
> or see [openpolemount.com/iv-pole-v3](https://openpolemount.com/iv-pole-v3/) for details.

**v2 — universal device holder.** Fully released and print-ready. Documented as a
universal holder (may fit a range of equipment; no confirmed compatibility list
yet — fit reports welcome). This is the version currently available via
print-on-demand.

**v1 — legacy.** Best repurposed as a pole-mounted accessory box that mounts
below the cradle.

## Specifications

Printed-part dimensions and a starting load rating. **Match your equipment's own
size and weight to these figures before printing** — if it fits the envelope, it
fits the cradle.

| Part | Printed size (L × W × H) | Load rating* |
|---|---|---|
| Equipment cradle v3 | ~125 × 100 × 66 mm | up to ~1.4 kg (3 lb) |
| Equipment cradle v2 | ~126 × 105 × 65 mm | up to ~1.4 kg (3 lb) |
| Pole mounting block | ~60 × 58 × 48 mm | — |

\* *Starting point, not a guarantee. Actual capacity depends on your material,
print settings, and print quality — see the [Print Guide](https://openpolemount.com/iv-pole-v3/print-settings/)
and [DISCLAIMER.md](DISCLAIMER.md). Verify safe support of your own load before use.*

## Community Fit Reports

> The notes here are **user-reported, not manufacturer claims, and not verified
> for any medical use.** OpenPoleMount makes no compatibility guarantee. Confirm
> fit, load suitability, and safety yourself before any use, and consult your
> healthcare provider before using any mount with medical equipment.

Makers have reported that the v3 and v2 form factors fit some home infusion
equipment (including units labeled Curlin CMS6000). We do not maintain or
guarantee a compatibility list. To share a fit report, please
[open an issue](https://github.com/GoR-XarraY/openpolemount/issues).

## Files

| File | Description |
|---|---|
| [`stl/OpenPoleMount_IV-Pole_v3.stl`](https://github.com/GoR-XarraY/openpolemount/raw/main/stl/OpenPoleMount_IV-Pole_v3.stl) | **Equipment cradle v3** — current design, form-fitted (available now) |
| `stl/OpenPoleMount_IV-Pole_v2.stl` | Equipment cradle v2 — universal device holder, available now (print 1x) |
| `stl/thumbscrew_v14_flat_Thandle.stl` | Thumbscrew for pole attachment (print 1x) |
| `stl/OpenPoleMount_IV-Pole_v1.stl` | v1 — legacy; best used as a pole-mounted accessory box |
| [`source/`](source/) | Native editable source files — Blender `.blend` for every design |

## Quick Start

1. **Download** the STL files from [Releases](https://github.com/GoR-XarraY/openpolemount/releases/latest)
2. **Print** the v3 cradle in PLA — see the [v3 Print Guide](https://openpolemount.com/iv-pole-v3/print-settings/); the [v2 Print Guide](https://openpolemount.com/iv-pole-v2/print-settings/) is available too
3. **Assemble** — see the [v3 Assembly Guide](https://openpolemount.com/iv-pole-v3/assembly/)
4. **Read the disclaimer** — [DISCLAIMER.md](DISCLAIMER.md)

No printer? v2 can be printed on demand and shipped at cost via Slant 3D / Teleport
— see [openpolemount.com](https://openpolemount.com/order/). (v3 print-on-demand
isn't set up yet.)

## Website & Documentation

**[openpolemount.com](https://openpolemount.com)** — full documentation, print
guide, assembly instructions, safety information

## Licensing

| Asset | License |
|---|---|
| Hardware (STL, STEP, CAD files) | [CERN-OHL-W-2.0](LICENSE) — derivatives must stay open |
| Documentation (docs/, README, images) | [CC-BY-SA-4.0](LICENSE-docs) |

## Contributing

Have an idea for a new IV pole accessory? See [CONTRIBUTING.md](CONTRIBUTING.md).

The OpenPoleMount block mounting standard is designed so any community-designed
accessory can attach to any compatible IV pole mount.

## Community

- [Printables listing](https://www.printables.com) *(link coming soon)*
- Open an [Issue](https://github.com/GoR-XarraY/openpolemount/issues) with questions or problems

---

*OpenPoleMount is an independent open source project. It is not affiliated with
Curlin Medical, Smiths Medical, Moog, or any IV pump manufacturer.*
