
<img src="../media/torso.png" height="250">

# Schematic
<img src="../media/wiring_schematic.png" height="200">

# BOM
Items marked with `*` are optional for using pogo pin connectors
| Item           | Quantity        | Unit Cost (USD)            | Cost          | Source          |  
| :------------- | :-------------: | :-------------:            | :-------------|   :-------------|
| XL330-M288-T                 | 22 |  26.29         | $578.38                   | [ROBOTIS](https://www.robotis.us/dynamixel-xl330-m288-t/)|
| XL330-M077-T                 | 2  |  26.29         | $52.58                    | [ROBOTIS](https://www.robotis.us/dynamixel-xl330-m077-t/)|
| U2D2                         | 1  |  35.31         | $35.31                    | [ROBOTIS](https://www.robotis.us/u2d2/?srsltid=AfmBOopnAfcYD4wZJd2mYGfl02LkN3lmzDXwg2oOkg-FG9G7V-jAIUyt)|
| FPX330-H101 4pcs Set         | 3  |  11.27         | $33.81                    | [ROBOTIS](https://www.robotis.us/fpx330-h101-4pcs-set/)|
| TTL Expansion Board          | 2  |  6.79          | $13.58                    | [ROBOTIS](https://www.robotis.us/3p-jst-expansion-board/)|
| Raspberry Pi 5a              | 1  |  80            | $80                       | [Digikey](https://www.digikey.com/en/products/detail/raspberry-pi/SC1112/21658257)|
| Raspberry Pi 5 active cooler | 1  |  9.50          | $9.50                     | [Sparkfun](https://www.sparkfun.com/raspberry-pi-active-cooler.html?src=raspberrypi)|
| Buck converter               | 1  |  11.00         | $11.00                    | [Amazon](https://a.co/d/34K1G3W)|
| Lipo batteries               | 2  |  31.49         | $62.98                    | [getfpv](https://www.getfpv.com/batteries/mini-quad-batteries/lumenier-850mah-4s-75c-lipo-battery-xt-30.html)|
| IMU                          | 1  |  34.95         | $34.95                    | [Adafruit](https://www.adafruit.com/product/2472)|
| Baby Carrier                 | 1  |  37.99         | $37.99                    | [Amazon](https://a.co/d/6YLBBi4)|
| XT30 Connector Female        | 1  |  8.99          | $8.99                     | [Amazon](https://a.co/d/beCXKoa)|
| SD card                      | 1  |  14.99         | $14.99                    | [Amazon](https://a.co/d/bTOPJQl)|
| M3x8 screw                   | 33 |  0.0545        | $1.80                     | [Mcmaster](https://www.mcmaster.com/91292A112/) |
| M2x8 screw                   | 4  |  0.0712        | $0.28                     | [Mcmaster](https://www.mcmaster.com/91292a832/) |
| M2x6 screw                   | 24 |  0.0878        | $2.11                     | [Mcmaster](https://www.mcmaster.com/91292a831/) |
| Female jumper wires          | 6  |  0.0582        | $0.46                     | [Amazon](https://a.co/d/gtiBsbT)|
| PLA Filament                 | 1.1kg  |  -         | $22                       | |
| Spring Piston 8pos*          | 24 |  0.0878        | $2.11                     | [DigiKey](https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/823-22-008-10-002101/1146974) |
| Spring Target 8pos*          | 6  |  0.0582        | $0.46                     | [Digikey](https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/419-10-208-00-006000/5176111)|
| CONN RCPT HSG 3POS 2.50MM*   | 14 |  0.0448        | $1.12                     | [DigiKey](https://www.digikey.com/en/products/detail/jst-sales-america-inc/EHR-3/527225) |
| 22-30AWG Crimp Tin*          | 42 |  -             | $2.52                     | [DigiKey](https://www.digikey.com/en/products/detail/jst-sales-america-inc/SEH-001T-P0-6/26213194) |
| Custom PCB*                  | 14 |  -             | $27                      | [PCBWay](https://www.pcbway.com/) |
|                              |    |  **Total**     | $1000.71 ($1033.92*)              | |

### Miscellaneous
- Power wires

# Torso
**3D Prints**
- [leader_mount](./3D_print_parts/leader_mount.STL) `x7` (Replace with [leader_mount_pogo_pin](./3D_print_parts/leader_mount_pogo_pin.STL) if using pogo pins)
- [back_cover_clip](./3D_print_parts/back_cover_clip.STL) `x2`
- [back_cover_lower](./3D_print_parts/back_cover_lower.STL)
- [back_cover_upper](./3D_print_parts/back_cover_upper.STL)
- [torso_lower](./3D_print_parts/torso_lower.STL)
- [torso_upper](./3D_print_parts/torso_upper.STL)
- [mount_pcb_clamp](./3D_print_parts/mount_pcb_clamp.STL) (If using pogo pins) `x7`

# G1 Limb Leaders
Screws and wires for leader assembly (included in XL330 servo box):
- M2x6mm self tapping screw
- M2x8mm self tapping screw
- TTL wires

**3D Prints**
- [G1_Arm_Leader_R_handle](./3D_print_parts/G1_Arm_Leader_R_handle.STL) `x2`
- [G1_Arm_Leader_trigger](./3D_print_parts/G1_Arm_Leader_trigger.STL) `x2`
- [G1_Leg_Leader_foot](./3D_print_parts/G1_Leg_Leader_foot.STL) `x2`
- [G1_Leg_Leader_knee_jnt_limit](./3D_print_parts/G1_Leg_Leader_knee_jnt_limit.STL) `x2`
- [G1_Leg_Leader_link_2](./3D_print_parts/G1_Leg_Leader_link_2.STL) `x2`
- [G1_Leg_Leader_link_3.1](./3D_print_parts/G1_Leg_Leader_link_3.1.STL) `x2`
- [G1_Leg_Leader_link_3.2](./3D_print_parts/G1_Leg_Leader_link_3.2.STL) `x2`
- [G1_Leg_Leader_link_4.1](./3D_print_parts/G1_Leg_Leader_link_4.1.STL) `x2`
- [G1_Leg_Leader_link_4.2](./3D_print_parts/G1_Leg_Leader_link_4.2.STL) `x2`
- [G1_Leg_Leader_L_link1](./3D_print_parts/G1_Leg_Leader_L_link1.STL)
- [G1_Leg_Leader_R_link1](./3D_print_parts/G1_Leg_Leader_R_link1.STL)
- [G1_Arm_Leader_L_link_1](./3D_print_parts/G1_Arm_Leader_L_link_1.STL)
- [G1_Arm_Leader_L_link_2](./3D_print_parts/G1_Arm_Leader_L_link_2.STL)
- [G1_Arm_Leader_L_link_3](./3D_print_parts/G1_Arm_Leader_L_link_3.STL)
- [G1_Arm_Leader_L_link_4](./3D_print_parts/G1_Arm_Leader_L_link_4.STL)
- [G1_Arm_Leader_L_link_5](./3D_print_parts/G1_Arm_Leader_L_link_5.STL)
- [G1_Arm_Leader_L_link_6](./3D_print_parts/G1_Arm_Leader_L_link_6.STL)
- [G1_Arm_Leader_R_link_1](./3D_print_parts/G1_Arm_Leader_R_link_1.STL)
- [G1_Arm_Leader_R_link_2](./3D_print_parts/G1_Arm_Leader_R_link_2.STL)
- [G1_Arm_Leader_R_link_3](./3D_print_parts/G1_Arm_Leader_R_link_3.STL)
- [G1_Arm_Leader_R_link_4](./3D_print_parts/G1_Arm_Leader_R_link_4.STL)
- [G1_Arm_Leader_R_link_5](./3D_print_parts/G1_Arm_Leader_R_link_5.STL)
- [G1_Arm_Leader_R_link_6](./3D_print_parts/G1_Arm_Leader_R_link_6.STL)
- [pogo_pin_adapter](./3D_print_parts/pogo_pin_adapter.STL) (If using pogo pins) `x4`
- [pogo_pin_pcb_spacer](./3D_print_parts/pogo_pin_pcb_spacer.STL) (If using pogo pins) `x4`

## Monitor Stand Adapter
- [Monitor_stand_attachment](./3D_print_parts/Monitor_stand_attachment.STL)
- [Monitor_stand_bracket](./3D_print_parts/Monitor_stand_bracket.STL)
- [monitor_stand_lock](./3D_print_parts/monitor_stand_lock.STL)