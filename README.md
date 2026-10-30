<div align="center">
    <img src="https://github.com/congatudo/congatudo-add-on/blob/main/images/logo.png?raw=true" alt="congatudo">
    <p align="center"><h2>Free your vacuum from the cloud</h2></p>
</div>

## What this fork changes

This add-on runs [Sloy/Congatudo](https://github.com/Sloy/Congatudo) (upstream Congatudo `2024.04` plus
fixes) instead of the upstream image. amd64 only.

- Room cleans mop the selected rooms when the water tank is inserted (upstream only vacuumed).
- A full mop after a room mop covers every room; stop works in mop mode.
- New Home Assistant binary sensors: "Dust bin attachment", "Water tank attachment", "Mop
  attachment". Use "Water tank attachment" to know whether the robot is set up for mopping.

Details, causes and how to use the sensors:
[What this fork changes](https://github.com/Sloy/Congatudo#what-this-fork-changes).

The add-on keeps the upstream config path (`/config/valetudo.json`), so it can replace the upstream
add-on without reconfiguration. Run only one of the two at a time: both use ports 4010/4030/4050.

---

[Congatudo](https://congatudo.cloud) add-on aims to be a vendor-agnostic abstraction and cloud replacement for Cecotec Conga vacuum robots
For more information, check out the [repository](https://github.com/congatudo/Congatudo)

# Documentation
The procedure for installing this add-on can be found in the [project documentation](https://congatudo.cloud/pages/installation/home-assistant-installation.html).

# Installation

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https://github.com/congatudo/congatudo-add-on)
