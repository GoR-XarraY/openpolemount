# Assembly Guide

!!! warning "Before You Start"
    Verify your printed parts pass all checks in the [Print Guide](print-settings.md)
    before assembly. Do not use parts with visible layer delamination, cracking,
    or significant warping.

## What You Need

| Item | Source |
|---|---|
| Printed cradle (`OpenPoleMount_IV-Pole_v1.stl`) | Print 1x |
| Printed thumbscrew (`thumbscrew_v14_flat_Thandle.stl`) | Print 1x |
| Standard home IV pole (~25mm / 1 inch diameter) | Your existing equipment |
| Curlin CMS6000 infusion pump | Your existing equipment |

No tools required — assembly is fully hand-tightened by design.

---

## Assembly Steps

### Step 1 — Thread the thumbscrew

Insert the thumbscrew into the threaded hole on the side of the cradle.
Turn **clockwise** by hand until it fully engages, then back off 2–3 turns
so the pole channel is open enough to slide onto the pole.

### Step 2 — Slide onto the pole

Position the cradle on the IV pole at the height where you want the pump.
The pole slides into the vertical channel on the back of the cradle.

### Step 3 — Tighten

Turn the thumbscrew **clockwise** by hand until it firmly contacts the pole.
Give it one additional firm quarter-turn. The cradle should not slide when
you push down on it with moderate force.

!!! danger "Do Not Over-Tighten"
    Over-tightening can crack the printed part. Hand-tight plus one quarter-turn
    is sufficient. If the cradle slips at this tension, inspect the print quality
    and reprint if needed — do not force beyond hand-tight.

### Step 4 — Install the pump

Lower the Curlin CMS6000 into the cradle from above. The pump's pole hook/lug
seats into the cradle pocket. Verify the pump is fully seated and does not rock
or tip.

### Step 5 — Verify stability

Before connecting any IV line:

- [ ] Cradle does not slide down the pole under firm downward pressure
- [ ] Pump does not tip or rock in the cradle
- [ ] IV tubing can exit the pump without creating strain on the mount
- [ ] IV pole base is fully spread and stable on the floor

---

## Adjusting Height

To reposition:

1. Remove the pump from the cradle
2. Loosen the thumbscrew 2–3 turns
3. Slide the cradle to the new height
4. Re-tighten the thumbscrew

Do not attempt to slide the cradle while the pump is seated in it.

---

## Removal

1. Disconnect the IV line from the pump first (follow your care provider's instructions)
2. Lift the pump straight up out of the cradle
3. Loosen the thumbscrew fully
4. Slide the cradle off the pole

---

## Troubleshooting

| Problem | Likely Cause | Solution |
|---|---|---|
| Cradle slides down the pole | Thumbscrew not tight enough or pole diameter too small | Tighten more; check pole diameter matches design spec |
| Pump rocks in the cradle | Wrong pump model or print tolerance issue | Verify this is a Curlin CMS6000; [open an issue](https://github.com/GoR-XarraY/openpolemount/issues) if pump doesn't fit |
| Thumbscrew won't turn smoothly | Print stringing in threads or warped thread hole | Clean threads with brush; if damaged, reprint thumbscrew |
| Pole doesn't fit the channel | Pole diameter differs from design | [Open an issue](https://github.com/GoR-XarraY/openpolemount/issues) with your pole diameter |
| Part cracked during assembly | Over-tightening or under-printed | Reprint at ≥35% infill, 6 walls; hand-tighten only |

---

!!! info "Need Help?"
    If your pump doesn't fit or you're having trouble with assembly,
    [open an issue on GitHub](https://github.com/GoR-XarraY/openpolemount/issues).
    Include a photo if possible — we want to help.
