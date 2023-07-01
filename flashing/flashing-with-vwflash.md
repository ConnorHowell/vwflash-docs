---
layout: default
title: Using VW_Flash
parent: Flashing
---

# Flashing Using VW_Flash
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Prerequisites
* Compatible OBD adapter Macchina A0 ([instructions for building a clone](https://github.com/Switchleg1/AMAleg)) or Tactrix OpenPort (genuine).
* Unlock FRF (`FL_8V0906259H__0001.frf` or `FL_5G0906259Q__0005.frf`)
* VW_Flash_GUI distribution package from ["Releases"](https://github.com/bri3d/VW_Flash/releases) on GitHub.

## Setting up your Hardware

* For Tactrix OpenPort, [install the latest OpenPort drivers](https://www.tactrix.com/index.php?Itemid=61).
* For Macchina A0/homemade clone, install drivers using this guide.

## Picking an interface

* Open the VW_Flash_GUI application. You should see a command window as well as the application GUI.
* Open the Interface menu and choose Select Interface.

<img src="/assets/images/select-dialog.png" width="700" alt="Screenshot of Select Interface Dialog" />

* To use an A0 over serial, pick the interface which reads `Silicon Labs CP210x USB to UART Bridge.`
* To use an A0 over Bluetooth, check "Scan for BLE devices" in the "Interface" menu, pick the interface which reads `BLE_TO_ISOTP`.
* To use J2534 / OpenPort, pick the J2534 interface you'd like to use.

