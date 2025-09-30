# Child-friendly Countdown Timer  
Electronic PCB and Front Panel to fit Hammond RL6655, designed in Kicad 9.0

## Main components
 - STM32C031C6: Cortex-M0+, 32kB flash, 12kB RAM, 45 IOs
 - 0.8 inch 7-segment displays SA08-11SURKWA
 - C&K D6 buttons
 - USB micro powered from a battery pack, 0.6mA in sleep.

## PCB parameters
Two layers, mix of surface mount and through hole components, ground plane fill.

## Bill of Materials
SMT Part numbers for LCSC (JLC) 
Through hole, SMTs not available at LCSC and mechanical parts from RS or Mouser.

## Front Panel
PCB with black solder mask, white silkscreen, cutouts for displays, LEDs, buttons, mounting holes. Replaces front panel on RL6655, main PCB is mounted behind it.

## Additional components needed
 - Either a 5V 0.5A PSU (phone charger) or portable battery with USB output
 - USB A to USB micro short cable for the portable battery
 - Cable ties to hold battery back to back of PCB
 - optional: Display filter material, 40x100mm, < 1mm thick.
 - for programming: STLINK-V3MINIE with ribbon cable from [STM32C0316-DK](https://www.st.com/en/evaluation-tools/stm32c0316-dk.html)
 - for programming: USB C cable to your laptop (USB C or USB A) from the STLINK
