# The Dondi Lib

Part nightlight, part art, part Internet of Things. This little bluetooth enabled box will surprise and delight. For more info go [here](https://www.hackster.io/jaredwolff/the-dondi-lib-a-bluetooth-low-energy-light-box-cc7d90).

## Version One

### Features

1. Bluetooth Low Energy with a Rigado BMD-300 (nRF52832)
1. Lithium Battery support
1. Motion support
1. PIR Amplifier (Motion)
1. External connections for button, DC power, battery and PIR
1. Tag-Connect SWD connection

### Rework

Please note that this is Version 1 of the board. There are several (reworkable) issues with this board. 

1. U7A.1 should be connected to D9.C
1. D4.2 should be connected to VDC
1. J2.1 missing connection to VSYS
1. U2 changed to a LED1642GW
1. Untuffed U6 to accomodate LED driver above
1. LED_OE (PWM_CLK) connected to LIS2DH_INT

### License

Released under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International Public License. More info [here](https://creativecommons.org/licenses/by-nc-nd/4.0/legalcode).

