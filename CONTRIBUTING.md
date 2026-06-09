# Contributing to OpenPoleMount

Thank you for wanting to help! This project exists because the 3D printing
community can solve real problems for real patients.

## Ways to Contribute

### 1. Report a Problem
Open an [Issue](https://github.com/GoR-XarraY/openpolemount/issues) if:
- A part doesn't fit your pole or pump model
- Print settings don't work for your setup
- You found a safety concern (please be specific)
- You have suggestions for improvement

### 2. Improve Existing Designs
1. Fork the repo on GitHub
2. Open the source files in `source/` with your CAD tool
3. Make your changes
4. Submit a Pull Request with:
   - What you changed and why
   - Photos or renders of the result
   - Updated STL in `stl/`
   - Updated STEP in `source/`

### 3. Add a New Accessory
Have an idea for a new IV pole accessory that uses the OpenPoleMount block?
1. Open an Issue first to discuss the design
2. Once design is agreed on, follow the same PR process above
3. New accessories go in: `accessories/<your-accessory-name>/`

## File Format Requirements

| Type | Format | Required |
|---|---|---|
| Print-ready | `.stl` or `.3mf` | Yes |
| Source CAD | `.step` / `.stp` | Yes — OSHWA requires editable source |
| Native CAD | `.f3d`, `.FCStd`, `.sldprt`, etc. | Strongly encouraged |
| Documentation | `README.md` with print settings | Yes |

## License

By contributing, you agree your contributions are licensed under the same
terms as the project:
- Hardware files: CERN-OHL-W-2.0
- Documentation: CC-BY-SA-4.0

## Medical Safety Note

This project is used by real patients. If you're contributing a design that
affects load-bearing parts:
- State the material and infill you tested with
- Describe any load or fit testing you performed
- Do not make clinical safety claims — we are a reference design, not a certified product
