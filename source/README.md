# Source CAD Files

This folder contains the **native, editable source files** for the OpenPoleMount
hardware designs. The designs are made in [Blender](https://www.blender.org/) —
free, open-source software — so anyone can open, edit, and remix these files
without buying CAD software.

## Files

| File | Design |
|---|---|
| `OpenPoleMount_IV-Pole_v3.blend` | IV Pole Cradle v3 (current, form-fitting) |
| `OpenPoleMount_IV-Pole_v2.blend` | IV Pole Cradle v2 (universal holder) |
| `OpenPoleMount_IV-Pole_v1.blend` | v1 (accessory box) |
| `OpenPoleMount_Pole_Mounting_Block_V1.blend` | Pole Mounting Block + thumbscrew interface |

The ready-to-print STL meshes exported from these sources live in [`stl/`](../stl/).

## Why Source Files Matter

Publishing editable source files (not just STL) is a requirement of true open
source hardware. STL files are like a PDF — anyone can read them but nobody can
easily edit them. These `.blend` files are the original documents — fully editable.

This satisfies the editable-source expectation of
[OSHWA certification](https://certification.oshwa.org), using an open-source
toolchain end to end.

## Editing

Open in Blender 3.x or newer. Units are millimeters at real-world scale — verify
scale before exporting STL for print (File → Export → STL, apply modifiers).
Derivatives are welcome under the hardware license
([CERN-OHL-W-2.0](https://cern-ohl.web.cern.ch/)) — see
[Contributing](https://openpolemount.com/contributing/).
