# Launch Heavy (Customization & Repairs)

The Launch Heavy Configurable Keyboard can be customized and personalized in a variety of ways. It is recommended to unplug all USB cables and devices from your Launch Heavy before changing keycaps or switches.

- [Connecting and using Launch Heavy](#connecting-and-using-launch-heavy)
- [Removing and installing keycaps](#removing-and-installing-keycaps)
- [Removing and installing switches](#removing-and-installing-switches)
- [Removing the PCBs](#removing-the-pcbs)

## Connecting and using Launch Heavy:

1. Connect the USB-C side of either the USB-C/USB-C or USB-C/USB-A cable to the Launch Heavy's center USB-C port.

![Launch ports](./img/ports-back.webp)

2. Connect the other side of the cable to your computer.
3. Connect any other USB devices to the four downstream USB ports on either side of the Launch Heavy.

## Removing and installing keycaps:

Launch Heavy uses only three sizes of uniform profile keycaps, which allows for a high degree of customization. Any two keycaps of the same size can be swapped on the keyboard, and several extras are included in the box.

**Tools required:** Keycap puller  
**Time estimate:** 25 minutes (to replace all keycaps)  
**Difficulty:** Easy <span style="color:green;">●</span>  

### Steps to remove a keycap:

1. Separate the two wire loops of the keycap puller and place them around two opposite corners of the keycap.
    - The keycap puller can be partially inserted over the sides of the key first, then twisted to go over the corners.

![Inserting the keycap puller](./img/keycap-removal-1.webp)

![Removing a keycap](./img/keycap-removal-2.webp)

2. Pull slowly but firmly (directly away from the keyboard) until the keycap slides off of the switch's stem.

![Removed keycap](./img/keycap-removed.webp)

#### Removing larger keycaps:

- The included keycap puller works on all three of Launch Heavy's keycap sizes.
- The six 2U keycaps (both `Space` bars, left `Shift`, numpad `0`, numpad `+`, and numpad `Enter`) have stabilizers, so be sure to pull both sides evenly.
    - These 2U keycaps take slightly more pulling force than the rest of the keycaps.

![Removing larger keycaps](./img/keycap-removal-15u-2u.webp)

#### Removing vertical keycaps:

- For the `launch_heavy_1.1` revision numpad PCB, when removing vertical 2U keycaps (numpad `Enter` and numpad `+`), the switch will come out of the socket with the keycap.

![Removing vertical keycap](./img/keycap-removal-vertical.webp)

- If you are not replacing the switch, remove it from the keycap and [install it back into the keyboard](#steps-to-install-a-switch) before putting on the new keycap.

### Steps to install a keycap:

1. Position the keycap on top of the switch.
2. Press the keycap down firmly until it's fully on the switch.
    - The keycap will be held onto the switch by friction.
    - The 2U keycaps with stabilizers require slightly more pressure to install.

![Installing a keycap](./img/keycap-installation.webp)

## Removing and installing switches:

Launch Heavy uses Kailh hot swap sockets, so key switches can be removed and installed without soldering. 

If you are changing all of the switches in your Launch Heavy, it is recommended to completely [remove the PCBs](#removing-the-pcbs), install the switches into the top case without the PCB, then install the PCBs into the case and onto the switch pins. This makes switch installation easier and reduces the likelihood of bending switch pins or damaging the PCBs.

If you are installing new switches, ensure that the switches you're installing are compatible with surface-mount (SMD) LEDs.

**Tools required:** MX-style switch puller  
**Time estimate:** ~1 minute per switch  
**Difficulty:** Medium <span style="color:orange;">●</span>  

### Steps to remove a switch:

1. [Remove the keycap](#removing-and-installing-keycaps) on the switch you wish to remove.
2. Place the two tongs of the switch removal tool into the switch's locking tabs on the top and bottom edges of the switch.

![Switch removal](./img/switch-removal.webp)

3. Pinch the tongs together to release the switch's locking clips from the chassis.
4. Pull the switch upwards out of the socket.
    - The switch's locking tabs can sometimes catch on the edges of the chassis cutouts. If the switch feels stuck, remove the tool and press the switch back down into place, then try removing it again.
    - Switches take more force to remove than keycaps.

![A removed switch](./img/switch-removed.webp)

### Steps to install a switch:

1. Make sure the switch's pins are straight.
    - If either of the pins is bent, gently bend it back into place.
    - **Caution:** Attempting to install a switch with bent pins may damage the PCB and/or switch.

![Bent vs. straight switch pins](./img/switch-pins.webp)

2. Orient the switch so the clear LED window aligns with the LED on the PCB, near the top of the socket.

![Switch orientation](./img/switch-orientation.webp)

3. Place the switch straight into the plate.
    - **Caution:** Forcing the pins into the hot swap socket if the pins are not properly aligned could damage the PCB and/or switch.
    - If you feel excessive resistance, pull the switch out, double-check that the pins are straight, and try installing the switch again.
4. Once you feel the pins plug into the hot swap socket, press the switch down with more force to snap it into place within the chassis.

![Switch installation](./img/switch-installation.webp)

## Removing the PCBs:

**Tools required:** Keycap puller, MX-style switch puller, and cross-head (Phillips) screwdriver  
**Time estimate:** 50 minutes  
**Difficulty:** High <span style="color:red;">●</span>  

If either of the PCBs in your Launch Heavy become damaged and need to be replaced, or if you are changing all of the switches in the keyboard, they can be removed and replaced using these instructions. The two PCBs are joined by a 100mm long, 20 pin, 0.5mm pitch FPC cable.

### Steps to remove the PCBs:

1. [Remove all of the keycaps](#removing-and-installing-keycaps) and [all of the switches](#removing-and-installing-switches).
    - The 2U stabilizers do not need to be removed.

![Launch Heavy with all keycaps removed](./img/all-keycaps-removed.webp)
![Launch Heavy with all switches removed](./img/all-switches-removed.webp)

2. Turn the keyboard over and remove the eight bottom panel screws.
    - The screws are set into adapters that may or may not come out with the screws.

![Bottom panel screws](./img/bottom-panel-screws.webp)

3. Remove the bottom panel.
    - If the magnetic lift bars are installed, they can be used as handles.

![Bottom panel removed](./img/internal-bottom.webp)

4. Disconnect and remove the flat ribbon cable between the main PCB (`launch 2.0`) and the numpad PCB (`launch_heavy 1.1`).
    - Slide the black latches away from the white connectors to free the cable.

![Ribbon cable](./img/ribbon-cable.webp)

5. Push each PCB up out of the chassis through one of the switch holes, then lift each PCB out of the chassis, one at a time.
    - For the main board, to avoid the USB-C port catching on the chassis, push through one of the bottom row switch holes and lift the bottom edge of the PCB first.

![Loose PCBs](./img/pcbs-removed.webp)

### Steps to install the PCBs:

1. Install all of the switches into the chassis.
    - The switches can also be installed after installing the PCBs, but installing the switches first is recommended because it reduces the risk of individual bent pins damaging the PCBs or switches during installation.
    - Make sure the switches are in the correct orientation with the LED window at the top.
    - The switches are not specific to their key/hole.

![Switches installed in chassis](./img/chassis-with-switches.webp)

2. Turn the chassis over and check that all of the switch pins are straight.
    - Look down the rows of pins from the sides of the chassis to identify any bent pins.
    - If any of the pins are bent when installing the PCBs, the switch or corresponding PCB may be damaged.
    - In the image below, the pin marked with a red arrow is an example of a pin that is bent and needs to be straightened.

![Switch pins in chassis (with a bent pin)](./img/chassis-switch-pin-check.webp)

3. Carefully line up the main PCB with the switch pins and place it in the chassis, starting with the USB-C port on the top edge.
    - Evenly press the PCB down until all of the switch pins are fully seated in their sockets.
    - It may help to pick up the keyboard and pinch to press both the PCB and the switches at the same time.
    - If you feel excessive resistance, stop, remove the PCB, and ensure that all of the switch pins are lined up.
    - The switch pins can be seen from the back of the sockets when they are fully seated, highlighted below.
    
![Switch pins visible through sockets](./img/pcb-switch-pins.webp)

4. Repeat the previous step for the numpad PCB.
5. Insert the ribbon cable into the white connector on both PCBs, then slide the black latches shut.
6. Install the bottom cover and its four screws, flip the keyboard over, and put all of the keycaps back on.
    - If any of the oval steel inserts came loose from the bottom cover, put them back into place before reinstalling the bottom cover.
        - The steel inserts are held in with glue, but are also held in place magnetically if the magnetic lift bar is installed. They can be re-glued with CA glue.
