


# Welcome
> **WARNING:**
> This project has not been tested yet. I cant guarantee that any of the circuits, PCBs, 3d models work or are accurate.

>This project is incomplete. The README isn't finished yet.

## Overview

This project is a tesla coil, DRSSTC to be more exact. Tesla coils are devices capable of generating extreme voltages that can be lethal if not operated correctly. 
> **Warning:** This project deals with high voltages. Replicate at your own risk.
 
 It is designed with a full bridge inverter connected to a MMC as the primary tank capacitor. This full bridge uses 4 parallel IGBT pairs driven by a single GDT. This GDT connects to the control circuit. Using a MIDI interrupter this coil has the ability to play music.

## Physical Design

The coil is designed with a skeleton topload and a vertical breakout point located in the middle of the topload. The primary coil is a pancake with a ground ring that is meant to protect it from flashover from topload.
>Note: The grounding ring is shouldn't be closed loop like shown in the image. This would short circuit the induced current and cause large current draw and energy loss.

![Image](https://github.com/miki407/DRSSTC/blob/main/Render.jpg)

## Circuit
The circuit for the control circuit and inverter are inspired by the UD2.7c and EasyBridge made by [Loneoceans](https://www.loneoceans.com/labs/index.htm). These circuits have been modified to fit the needs of this project.
The interactive BOM of these boards are here:
[Inverter](https://htmlpreview.github.io/?https://github.com/miki407/DRSSTC/blob/main/Full%20Bridge/Full%20Bridge/bom/ibom.html)
[Control circuit](https://htmlpreview.github.io/?https://github.com/miki407/DRSSTC/blob/main/Controller/DRSSTC%20controller/bom/ibom.html)

## Future additions

* Polyphonic MIDI interrupter
* Testing data
* Assembly guide
* Full BOM 

## Mistakes and Suggestions 
If I made any mistakes or if you want to suggest anything you can contact me on milosmilicevic575@gmail.com.
