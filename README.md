# M224A1 — 60mm Handheld Mortar

[![Discord](https://img.shields.io/badge/Discord-Join%20Us-5865F2?logo=discord&logoColor=white)](https://discord.gg/PFxWc9W7zD)
[![License](https://img.shields.io/badge/License-APL-blue)](LICENSE)

The **M224A1** is a lightweight, shoulder-carried, inventory-loaded handheld mortar system intended to move with the Forward Line of Troops and provide direct-lay and organic indirect fires.

> Thank you to everyone who assisted in making this possible.
>
> Bug reports, issues, and suggestions belong in the proper channels of the [Discord](https://discord.gg/PFxWc9W7zD).

---

## Contents

- [Overview](#overview)
- [Technical Specifications](#technical-specifications)
- [Rounds](#rounds)
- [User Manual](#user-manual)
  - [Placement](#placement)
  - [UI & Firing](#ui--firing)

---

## Overview

This is **not** a vanilla mortar. It is carried and assembled by a single person from the launcher slot, loaded by the gunner without leaving the gun, and has no gunner's sight.

- Carried in the **launcher slot**; placed via keybind using a "ghost" preview.
- Once deployed, the M224 acts as a **turret** — reload pulls directly from player inventory.
- Custom animations and particle effects.
- Reposition the tube or pick it up through **look-interactions**.

---

## Technical Specifications

| Specification | Value |
| --- | --- |
| Tube Weight | *TBD* |
| Minimum Range | *TBD* |
| Maximum Range | *TBD* |
| Maximum Traverse | 45° |
| Maximum Elevation | 80° |
| Minimum Elevation | 45° |
| Reload Time | *TBD* |
| Maximum Rate of Fire | *TBD* |

---

## Rounds

| | **M722 — HE** | **M722B — WP** |
| --- | --- | --- |
| **Type** | High Explosive | White Phosphorus |
| **Detonation** | Direct Impact or Airburst | Direct |
| **Charge** | 0 / 1 | 0 / 1 |
| **Weight** | *TBD* | *TBD* |
| **Minimum Safe Distance** | *TBD* | *TBD* |
| **Notes** | — | Plume Duration: *TBD* |

---

## User Manual

The M224A1 tube is classified as a **ROCKET LAUNCHER** and occupies that slot.

> **Note:** The inventory item itself is *not* the fireable variant. Placing it on the ground does nothing.

The shells are classified as **GRENADES** and are found under that slot.

### Placement

1. From a position you intend to fire from, equip the tube from your **launcher slot**.
2. With the tube in hand, enter placement mode with the default action key (**`F`** on PC — rebindable in settings).
3. A moving M224 **"ghost"** will track your camera position. Orient yourself on flat ground toward your direction of fire and press the default fire button (**`LMB`** on PC).

Once placed, the mortar turret is emplaced and ready to enter. It can be picked up and repositioned via default interactions while looking at the tube.

> **Repositioning:** You must be within **`<GET DATA>` m** of the reposition point. The ghost disappears if you leave that radius.

### UI & Firing

You've entered the mortar and are ready to fire. By default the weapon is **UNLOADED** — this is intentional, since once a round is chambered it can only be fired out.

The default selection is:

> **High Explosive** &nbsp;|&nbsp; **Charge 0** &nbsp;|&nbsp; **Direct Impact**

Change these by looking down at the **trigger guard** and interacting with the options there.

> **Note:** Changing ammunition type applies to the **next loaded round**. To fire WP, either fire your currently loaded round first or select WP *before* loading.

**Reading the UI**

- A scrolling **azimuth display** sits at the top of your screen, showing both mils and degrees.
- Your **elevation bubble** is slightly off-center in the bottom right — see the graphic below.

> **Note:** The UI glows at night and under night vision to aid visibility.

<!-- Replace with your actual graphic path -->
<p align="center">
  <img src="docs/images/elevation_bubble.png" width="500" alt="Elevation bubble reference">
</p>

**Firing**

Once dialed in on the proper bearing and elevation, fire using the default fire interaction. Reload with the default reload action — the round is chambered once the reload sound ends.

> **⚠️ Warning:** The muzzle has an overpressure damage radius of roughly **1 meter**. Keep nearby heads down.
