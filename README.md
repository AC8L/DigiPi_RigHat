# DigiPi RigHat
## (Yet an other interface hat for famous DigiPi)

This is an interface hat for a DigiPi by KM6LYW (www.digipi.org).
I am releasing fabrication files under open source license so anyone can order PCB's with SMD mounted components.
Feel free resuing materials as you wish, if someone decides to produce PCB's for commerical use, I am fine with that too and have no objection.

<img src="https://github.com/AC8L/DigiPi_RigHat/blob/main/images/Installed_With_Panel.jpeg" width=50% height=50%>
<img src="https://github.com/AC8L/DigiPi_RigHat/blob/main/images/Installed_With_Panel_noEnclosure.jpeg" width=50% height=50%>
<img src="https://github.com/AC8L/DigiPi_RigHat/blob/main/images/Installed.jpeg" width=50% height=50%>

## Schematic
Schematic is based on KM6LYW's original documentation at www.digpi.org. PCB was designed to utilize the SMD resistors and MOSFET to fit under the tight Pi Zero configuration and be flush with the display hat.
<img src="https://github.com/AC8L/DigiPi_RigHat/blob/main/images/Schematic.png" width=50% height=50%>

## Through-hole components
These are the additional THT components to be sourced for the final assembly:

- 2.54mm Double Row Female Long Pin 11mm Breakaway PCB Board Pin Header Connector 
https://a.co/d/0CLkeeG

- TRRS Connector
https://a.co/d/cTMyE9t

- LED's
https://a.co/d/4QbojtL

- JST-XH 3-pin Male-Female pair
https://a.co/d/czNhTzQ

## PCB Ordering and final assembly
1. Use fabrication files in DigiHat_Fabrication_Files folder to order the PCB. PCB will arrive with resistors and thre MOSFET soldered. Optionally, you can order PCB front panel as well, which will give your DigiPi professional look. There are two versions of the front panel - with holes for LED's and without.
2. Solther PIN header and TRRS connector to the bottom of the PCB.
3. Sother LED's at the top, pay attention to the polarity. The negative pin (short pin, the cathode) goes to the square pad.
4. Bend JST male pins 90 degree and solder to the bottom of the PCB as shown in the photo:
<img src="https://github.com/AC8L/DigiPi_RigHat/blob/main/images/Assembled_Bottom.jpeg" width=25% height=25%>
5. Solther female JST cable assembly to the sound card:
<img src="https://github.com/AC8L/DigiPi_RigHat/blob/main/images/JST_SoundCard1.jpeg" width=25% height=25%>
<img src="https://github.com/AC8L/DigiPi_RigHat/blob/main/images/JST_SoundCard2.jpeg" width=25% height=25%>
6. Put everything together:
<img src="https://github.com/AC8L/DigiPi_RigHat/blob/main/images/Installed.jpeg" width=25% height=25%>


## Interface connection cables
The TRRS pins has been chosen such a way that hat is compatible with DigiRig cables. So far, successful tests were made with:
- (tr)USDX audio/PTT cable: https://digirig.net/product/usdx-cable-for-digirig-mobile/
- Baofeng audio cable: https://digirig.net/product/baofeng-cords-kit-for-digirig-mobile/

## 3D printed enclosure (work in progress)
Enclosure 3D models at thingiverse: https://www.thingiverse.com/thing:6478217.
Includes matched 3D-printable front panels as well as an alternatice to PCB-version of front panels.

