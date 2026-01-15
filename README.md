# WarlordsTemplate

## English

### Overview

This repository contains a `description.ext` file configured as a **Warlords mission template for Arma 3**. It is intended to be used as a base and **must be customized** before running the mission.

Below is a breakdown of the file **by configuration blocks**, not by line numbers, explaining what **must** be changed and what **can** be changed.

---

### Mandatory Configuration

#### Mission Information

You are required to customize the basic mission metadata:

* `onLoadMission` – Mission description shown while loading
* `onLoadName` – Mission name
* `dev` – Your nickname
* `author` – Mission author
* `min/maxPlayers` - Player limits

Leaving default values here is not allowed.

#### `class CfgWLRequisitionPresets`  **(REQUIRED)**

You **must**:

* Add **all of your custom unit and vehicle classes** here
* Ensure every asset used in the mission is registered

If your classes are missing here, they will not be available in Warlords.

[My classes list](https://github.com/KaifKol/A3-classNames)

### Optional Configuration

#### `class CfgWLFactionAssets`

Controls which assets are available per faction.

* Modify this if you want to restrict or expand faction-specific units

#### `class CfgWLAssetCostOverride`

Allows overriding default requisition costs for assets.

* Use this to rebalance units and vehicles
* Optional, but useful for fine-tuning gameplay

### Notes

* This template assumes you understand Arma 3 Warlords configuration
* Always verify classnames via the Config Viewer
* Test the mission after every major change

---

<p align="center" style="font-size: 28px; font-weight: bold;">
    Developed by the RallyPoint community
</p>
<p align="center">
  <a href="https://discord.gg/hJj45jUdjT">
    <img src="https://i.postimg.cc/pXzW7R3X/1.png" width="1500">
  </a>
</p>



