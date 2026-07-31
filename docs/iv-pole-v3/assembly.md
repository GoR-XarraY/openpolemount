# Assembly Guide — IV Pole Mount v3

!!! warning "Before You Start"
    Verify your printed parts pass all checks in the [Print Guide](print-settings.md)
    before assembly. Do not use parts with visible layer delamination, cracking,
    or significant warping.

!!! info "V3 vs V1/V2 — What's Different"
    The assembly process for v3 is identical to v1 and v2. The v3 cradle has a
    smaller, more form-fitting pocket shaped around the equipment, but the
    same pole channel, thumbscrew interface, and OpenPoleMount block standard.
    These instructions apply to all three versions.

## What You Need

| Item | Source |
|---|---|
| Printed cradle ([`OpenPoleMount_IV-Pole_v3.stl`](https://github.com/GoR-XarraY/openpolemount/raw/main/stl/OpenPoleMount_IV-Pole_v3.stl) — see [Print Guide](print-settings.md)) | Print 1x |
| Printed thumbscrew (`thumbscrew_v14_flat_Thandle.stl`) | Print 1x |
| Standard home IV pole (~25mm / 1 inch diameter) | Your existing equipment |
| Your device (equipment to be mounted) | Your existing equipment |

No tools required — assembly is fully hand-tightened by design.

---

## Assembly Steps

### Step 1 — Thread the thumbscrew

Insert the thumbscrew into the threaded hole on the side of the cradle.
Turn **clockwise** by hand until it fully engages, then back off 2–3 turns
so the pole channel is open enough to slide onto the pole.

![T-handle thumbscrew close-up on V3 mount](../images/iv-pole-v3/v3-thumbscrew-closeup.jpg)
*T-handle thumbscrew threaded into the mount — hand-tight only*

### Step 2 — Slide onto the pole

Position the cradle on the IV pole at the height where you want the device.
The pole slides into the vertical channel on the back of the cradle.

### Step 3 — Tighten

Turn the thumbscrew **clockwise** by hand until it firmly contacts the pole.
Give it one additional firm quarter-turn. The cradle should not slide when
you push down on it with moderate force.

![V3 mount rear view — pole clamp and thumbscrew](../images/iv-pole-v3/v3-mount-rear.jpg)
*Rear/underside view showing the thumbscrew boss engaged with the pole*

!!! danger "Do Not Over-Tighten"
    Over-tightening can crack the printed part. Hand-tight plus one quarter-turn
    is sufficient. If the cradle slips at this tension, inspect the print quality
    and reprint if needed — do not force beyond hand-tight.

### Step 4 — Install your device

Lower your device into the cradle from above. Because the v3 pocket is
form-fitted to the equipment body, it should seat snugly with very little side play.
Verify the device is fully seated and does not rock or tip.

![Equipment cradle v3 — device seated](../images/iv-pole-v3/v3-mounted-front.jpg)
*The device seats in the pocket with the front face accessible, cabling free to exit*

### Step 5 — Verify stability

Before connecting any IV line:

- [ ] Cradle does not slide down the pole under firm downward pressure
- [ ] Device does not tip or rock in the cradle
- [ ] Cabling can exit the device without creating strain on the mount
- [ ] IV pole base is fully spread and stable on the floor

![V3 mount — 3/4 angle view](../images/iv-pole-v3/v3-mounted-angle.jpg)
*Completed installation — device in the form-fitting v3 cradle, mount secure on pole*

---

## Adjusting Height

To reposition:

1. Remove the device from the cradle
2. Loosen the thumbscrew 2–3 turns
3. Slide the cradle to the new height
4. Re-tighten the thumbscrew

Do not attempt to slide the cradle while the device is seated in it.

---

## Removal

1. Disconnect any lines or cabling from the device first (follow your care provider's instructions)
2. Lift the device straight up out of the cradle
3. Loosen the thumbscrew fully
4. Slide the cradle off the pole

---

## Troubleshooting

| Problem | Likely Cause | Solution |
|---|---|---|
| Cradle slides down the pole | Thumbscrew not tight enough or pole diameter too small | Tighten more; check pole diameter matches design spec |
| Device doesn't seat fully / feels tight | Print tolerance/shrinkage variance — v3's pocket is form-fitted with less clearance than v2 | [Open an issue](https://github.com/GoR-XarraY/openpolemount/issues) with your printer/material; v2's more open pocket is a fallback |
| Thumbscrew won't turn smoothly | Print stringing in threads or warped thread hole | Clean threads with brush; if damaged, reprint thumbscrew |
| Pole doesn't fit the channel | Pole diameter differs from design | [Open an issue](https://github.com/GoR-XarraY/openpolemount/issues) with your pole diameter |
| Part cracked during assembly | Over-tightening or under-printed | Reprint at ≥25% infill, ≥1 mm walls; hand-tighten only |

---

!!! info "Need Help?"
    If your device doesn't fit or you're having trouble with assembly,
    [open an issue on GitHub](https://github.com/GoR-XarraY/openpolemount/issues).
    Include a photo if possible — we want to help.
