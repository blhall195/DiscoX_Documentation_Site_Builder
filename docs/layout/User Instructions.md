---
title: User Instructions
layout: default
nav_order: 2
---
# User Instructions
{: .no_toc }

These are the the instructions for the latest firmware release, you may be using an older version of the DiscoX software on your device. To update to the latest version follow these instructions.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Buttons

The DiscoX has four buttons, labeled 1–4 in the image below. Pressing 1 takes a reading, 2 activates Disco mode, and holding 3 opens the settings menu. Button 4 turns the device on/off. 

In menu mode, buttons 1–3 have different functions: 1 moves up the menu, 2 moves down, and 3 selects an item.

<img src="{{ '/assets/images/buttons.jpg' | relative_url }}" alt="buttons">

## Taking readings

To take a reading, press and hold button 1, or press it for longer than 100 ms (shorter presses are ignored). After you press the button, the DiscoX stays red until it detects the device is stable. Once stable, it turns green and records the reading.

<img src="{{ '/assets/images/taking-a-Reading.jpg' | relative_url }}" alt="taking a reading">

The DiscoX includes a leg-detection algorithm that triggers when it gets three consecutive readings where the compass, clino, and magnetometer values all fall within a set tolerance. When a leg is detected, the DiscoX flashes and beeps 3 times then turns purple.

<img src="{{ '/assets/images/leg detected.jpg' | relative_url }}" alt="leg detected">

## Display

The display shows the data from your most recent reading. When Bluetooth is disconnected, readings are stored in memory. The count of stored readings appears next to the battery icon at the top of the screen.

<img src="{{ '/assets/images/Screen.jpg' | relative_url }}" alt="screen">

## Blutooth & memory

The DiscoX works with current versions of SexyTopo and TopoDroid. It’s always advertising over Bluetooth, so nearby devices will pick it up. Once connected, a BT icon appears in the top-left of the screen and you will be able to send live readings to your phone. If stored readings are present, the device will transmit them to your phone after connecting; this can take a few seconds, longer if many readings are queued. DO NOT turn the DiscoX off during this period or your readings will be lost.

*Feature request:* In future versions of the software I'll make it so you can save the latest 10 reading backup files to memory so you can retrive them if you run into connectivity/upload issues. 

Your DiscoX will come with a unique name e.g. DiscoX_Sasquatch, this name can only be changed by opening the case and programming the Bluetooth module directly. If you name a specific name in mind let me know and I can name it before assebling one.  

## Settings

There are two ways to change the DiscoX settings: using the onboard menu, or editing a more comprehnsive settings.toml file after connecting the device to your PC.

### DiscoX onboard menu

To enter the onboard menu press and hold button 3. 

<img src="{{ '/assets/images/menu.jpg' | relative_url }}" alt="menu">