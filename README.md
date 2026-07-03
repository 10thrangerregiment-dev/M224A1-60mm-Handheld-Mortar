<div align="center">

# M224A1 — 60mm Handheld Mortar

**A lightweight, shoulder-carried, inventory-loaded mortar system built to move with the Forward Line of Troops — direct-lay and organic indirect fires, one gunner, no crew.**

[![Discord](https://img.shields.io/badge/Discord-Join%20Us-5865F2?logo=discord&logoColor=white)](https://discord.gg/PFxWc9W7zD)
[![License](https://img.shields.io/badge/License-APL-blue)](LICENSE)
[![Game](https://img.shields.io/badge/Arma-Reforger-2d2d2d)](https://reforger.armaplatform.com/)

*Thank you to everyone who assisted in making this possible.*

Bug reports, issues, and suggestions belong in the proper channels of the [Discord](https://discord.gg/PFxWc9W7zD).

</div>

---

## Contents

- [Overview](#overview)
- [Technical Specifications](#technical-specifications)
- [Rounds](#rounds)
- [User Manual](#user-manual)
  - [Inventory](#inventory)
  - [Placement](#placement)
  - [Fire Control](#fire-control)
  - [Reading the UI](#reading-the-ui)
  - [Firing](#firing)
- [Safety Notes](#safety-notes)

---

## Overview

This is **not** a vanilla mortar. It is carried and assembled by a single person from the launcher slot, loaded by the gunner without ever leaving the gun, and fired without a gunner's sight — direct lay, the way a handheld 60 is meant to be run.

|   |   |
|---|---|
| 🎒 | Carried in the **launcher slot** — placed via keybind using a live **ghost preview** |
| 🎯 | Once deployed, the M224 acts as a **turret**; reload pulls directly from the gunner's inventory |
| 🔧 | **Reposition** the tube or pick it up through look-interactions — no menus |
| ✨ | Custom animations, custom particle effects, custom fire-control UI |

---

## Technical Specifications

| Specification | Value |
| --- | ---: |
| Tube weight | *TBD* |
| Minimum range | *TBD* |
| Maximum range | *TBD* |
| Traverse | ±45° |
| Elevation | 45° – 80° |
| Reload time | *TBD* |
| Maximum rate of fire | *TBD* |

---

## Rounds

| | **M722 — HE** | **M722B — WP** |
| --- | :---: | :---: |
| **Type** | High Explosive | White Phosphorus |
| **Detonation** | Impact or Airburst | Impact only |
| **Charge** | 0 / 1 | 0 / 1 |
| **Weight** | *TBD* | *TBD* |
| **Minimum safe distance** | *TBD* | *TBD* |
| **Notes** | — | Plume duration: *TBD* |

---

## User Manual

### Inventory

The M224A1 tube is classified as a **ROCKET LAUNCHER** and occupies that slot.
The shells are classified as **GRENADES** and are found under that slot.

> [!NOTE]
> The inventory item itself is **not** the fireable variant — placing it on the ground does nothing. Deploy it (below) to fire.

### Placement

1. From the position you intend to fire from, equip the tube from your **launcher slot**.
2. With the tube in hand, enter placement mode with the default action key — **`F`** on PC (rebindable in settings).
3. A moving M224 **ghost** tracks your camera. Orient on flat ground toward your direction of fire and press the default fire button — **`LMB`** on PC.

Once placed, the mortar is emplaced and ready to enter. Pick it up or reposition it through the default look-interactions on the tube.

> [!TIP]
> **Repositioning:** you must stay within ***TBD* m** of the reposition point — the ghost disappears if you leave that radius.

### Fire Control

You've entered the mortar and are ready to fight the gun. The weapon starts **UNLOADED** by design — once a round is chambered, the only way it comes out is downrange.

The default selection is:

<div align="center">

**HIGH EXPLOSIVE** &nbsp;·&nbsp; **CHARGE 0** &nbsp;·&nbsp; **IMPACT**

</div>

Change any of these by looking down at the **trigger guard** and using the interactions there.

> [!IMPORTANT]
> Ammunition selection applies to the **next loaded round**. To fire WP, either send the round already chambered or select WP *before* loading.

### Reading the UI

- A scrolling **azimuth tape** sits at the top of your screen, reading in both **mils and degrees**.
- Your **elevation bubble** sits just off-center in the bottom right — see below.
- The UI **glows at night and under night vision**.

<!-- Replace with your actual graphic path -->
<p align="center">
  <img src="docs/images/elevation_bubble.png" width="500" alt="Elevation bubble reference">
</p>

### Firing

Dial onto your bearing and elevation, then fire with the default fire interaction.
Reload with the default reload action — **the round is chambered when the reload sound ends.**

---

## Safety Notes

> [!WARNING]
> The muzzle has an overpressure damage radius of roughly **1 meter**. Keep nearby heads down — the assistant gunner's especially.

---

<div align="center">

Made for the milsim community · Fire missions welcome

[Discord](https://discord.gg/PFxWc9W7zD) · [Report an issue](https://discord.gg/PFxWc9W7zD)

</div>
