# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project uses semantic versioning.

## [Unreleased]

### Added
- IV Pole Mount v3 documentation (`docs/iv-pole-v3/`) — overview/photos, print guide,
  assembly guide — a smaller, more form-fitting cradle pocket, built from user
  feedback on v2
- 9 new v3 product photos, processed and published under `docs/images/iv-pole-v3/`
- v3 promoted to the primary/lead design on the homepage, README, and nav

### Changed
- v2 repositioned as a **universal device holder**: the CMS6000-specific
  recommendation was removed; v2 now documents that its more open pocket may fit
  several infusion pumps or other devices, with no confirmed compatibility list yet,
  and invites community fit reports
- Homepage, README, nav, and social share image (OG/Twitter) updated to lead with v3
- `docs/testing.md` — added a scope note clarifying the destruction testing applies to
  the v1/v2 shape; v3 has not yet been separately tested
- **Non-device framing pass** — README, website docs, and social/SEO metadata reworded
  to describe OpenPoleMount as general-purpose mounting hardware (universal equipment
  cradle) rather than a pump-specific accessory. Specific-pump fitment is now presented
  only as user-reported example/community fit notes, not as manufacturer claims. Keeps
  the project a non-medical-device under FDA's intended-use framework. See
  `REGULATORY-CLASSIFICATION.md` (repo root — intentionally outside the docs site)

### Known Issues / Pending
- v3 STL release files are not yet published — the working files in `stl/` are not in
  the release-ready format used for v1/v2. Print-on-demand ordering and downloadable
  STL links for v3 are not yet live.

## [1.1.0] - 2026-06-17

### Added
- IV Pole Mount v2 (`OpenPoleMount_IV-Pole_v2.stl`) — revised exterior shape, functionally identical to v1
- Documentation for IV Pole Mount v2 (same specs, print settings, and assembly as v1)
- Variant comparison table on the home page

## [1.0.0] - 2026-06-08

### Added
- Initial release: IV pole cradle for Curlin CMS6000 infusion pump (`OpenPoleMount_IV-Pole_v1.stl`)
- Thumbscrew for pole attachment (`thumbscrew_v14_flat_Thandle.stl`)
- CERN-OHL-W-2.0 hardware license
- CC-BY-SA-4.0 documentation license
- Medical liability disclaimer (DISCLAIMER.md)
- Documentation website at openpolemount.com
- Print guide with material and infill requirements
- Assembly instructions
- Contributing guide and Code of Conduct
