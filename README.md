# Latching_Mouse_One_With_nRF52840DK
This code base takes the peripherals_hids_mouse (BLE) code template. Modifies it to make button 1 on the DK as a latching mouse one button for the connected client.

## Why?

Some video games require a task called "farming" where a certain repetitive task usually requires the player to hold the mouse one button, a.k.a left mouse click, for a long period.

## To pair

Pair device with a bluetooth capability, once pressed "connect" to "Nordic_HIDS_mouse". Press "BUTTON 1" to complete pairing. 

This code base allows the device to be connected to two devices

## Some features:

Mode button, BUTTON 1

Modes:

- Mode 1: Latching left (BUTTON 3) and right mouse (BUTTON 4) click
- Mode 2: iOS shutter button (BUTTON 2) which is the volume up button, drain battery by 10% (BUTTON 3), and increase battery by 10% (BUTTON 4)