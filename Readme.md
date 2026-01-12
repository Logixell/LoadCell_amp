# Load Cell Amplifier
## Board: B2202-R02
![Board](Assets/B2202-R02_3d.png)
This board is a Wheatstone Bridge amplifier intended for use with standard strain gauge load cells commonly used for weight measurement.  
### Overview
Load Cells are comonly use in conjunction with the HX711 Amplifier AD Module.  This 24 bit converter is ideal for Accurate slow measurements.  However, if you need high speed measurements this board converts the low signal voltages to voltages required by a high speed DAC.
### Description
This amplifer board is intended to be glued direcly onto the load sensor in order to keep the 4 wheatstone output wires of the load sensor as short a possible.  This will reduce noise pickup and allows the higher voltage signal to travel the longer distance to the DAC or direcly to Arduino Analog inputs.

### Specifications
The Amplifier used on this board is the Microchip MCP6009 which has enhanced EMI Protection.  The Supply voltage range is 1.8V to 5.5V.  This makes it compatible with 5V and 3.3V systems.

The signal output is offset by 1/2 of VIN to be able to read load cell force in both directions.  ie: 0V to 1/2VIN for pulling force and 1/2Vin to VIN for pushing force.

### Applications
High speed motor force feedback for robotics etc...
