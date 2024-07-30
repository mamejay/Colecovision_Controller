# Colecovision Controller
Controller for colecovision  

author: Jay Convertino 
  - Modified: Mamejay

date: 2024/07/30

## Changes


- Found original devs board had the fire buttons the wrong way around.  When playing games like Loadrunner, digging holes left and right are the opposite.  This has been corrected
- Also I have included a SMD version for the diodes

license: MIT (All files in repo)

## Release Versions
### Current
  - release_v1

### Past
  - none
  
## Requirements
  - KiCad v8

## Building
  - KiCad can generate any gerbers you are looking for.

## Parts list
|  REF  |      PART NUMBER      | QUANTITY |
|:---   |:---                   |:---      |
|D1-D28 |1N914                  |28        |
|S1-S18 |Omron B3F-10XX         |18        |
|J1     |RB-GEN-5839(cable)     |1         |
|H1-H8  |#4 x 5/8" Pan,Sheet    |8         |
|NA     |SHELL TOP (3D print)   |1         |
|NA     |SHELL BOT (3D print)   |1         |
|NA     |NUMPAD (3D print)      |12        |
|NA     |DPAD (3D print)        |1         |
|NA     |FIRE BUTTON (3D print) |2         |

## Assembly Tips
  - 3D print using ABS plastic.
    - 100.5% for shell size
    - 100% size for all buttons
  - Single sided PCB
  - Only the smallest diode footprint need to be installed vertically.
  - 8 Screws 
    - 5/8th inch long at most.
    - #4 screw 0.112 inch diameter.
    - Course thread (sheet metal type).
    - Pan Head no larger then 3/16th of an inch.
