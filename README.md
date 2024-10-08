# Mega Duck GB IPS Adapter
A simple adapter for the GB RIPS V5 Display to a Mega Duck / Cougar Boy.

<img src="./res/adapter.png" alt="drawing" width="600"/>

## Overview
This adapter enables the easy use of a Game Boy RIPS V5 display replacement for a Mega Duck handheld without any soldering inside the handheld.
The pinout of the Mega Duck display and the IPS display, as well as the idea for this, are based on Ruud van Falier's great hackaday article [Mega Duck (a.k.a. CougarBoy) IPS screen mod](https://hackaday.io/project/191431-mega-duck-aka-cougarboy-ips-screen-mod).

## BOM
| **Reference** | **Part** | **Link** |
---------|------|------|
|FPC1    | FFC connector with 18 pins, 0.5mm pitch, bottom contacts | [LCSC](https://www.lcsc.com/product-detail/FFC-FPC-Flat-Flexible-Connector-Assemblies_XUNPU-FPC-05F-18PH20_C2856802.html)|

## PCB
The thickness of the PCB does not matter too much, regular 1.6 mm thickness is fine.

You can also find the BOM and P&P file in the gerber folder, so it can be easily ordered with the FFC connector pre-assembled.

## Usage
* For most general instructions, check [Ruud van Falier's guide](https://hackaday.io/project/191431-mega-duck-aka-cougarboy-ips-screen-mod)
* To allow for an easy install, solder female pin headers onto the bottom of the PCB (top side is marked with "TOP SIDE").
* The Mega Duck display connector pins are shorter than usual, so grind the plastic of the female pin headers of the adapter down to the height of the pin headers of the original display. Or even better find one with the correct height, but I haven't found one yet :).
* Place the adapter board onto the Mega Duck display connector, such that the marking "LINK PORT" shows towards the link port of the Mega Duck.
* If you also want to install the contrast wheel replacement for brightness control and OSD access as described in [Ruud van Falier's article](https://hackaday.io/project/191431-mega-duck-aka-cougarboy-ips-screen-mod), you can find the pads to solder to on the adapter as P13, P15, P17, P18 (note that the images in this repo show an older version which did not include the P13 pad yet).
* For easier display installation, you can also find a 3D printable bracket [by retroboybr here on Thingiverse](https://www.thingiverse.com/thing:6590836).

## Disclaimer
**Use the files and/or schematics to build your own board at your own risk**.
This board works fine for me, but it's a simple hobby project, so there is no liability for errors in the schematics and/or board files.
**Use at your own risk**.
