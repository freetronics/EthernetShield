Freetronics Ethernet Shield
===========================
Copyright 2010 Freetronics Pty Ltd  
Freetronics site:  <www.freetronics.com>  
Freetronics email: <info@freetronics.com>  

************************************************************************
** WARNING: THIS IS A WORK IN PROGRESS AND PROBABLY BROKEN RIGHT NOW. **
** DON'T TRY TO FAB THIS BOARD OR IT WILL BE A WASTE OF TIME / MONEY! **
************************************************************************

10/100base-T Ethernet shield for the Arduino Duemilanove, TwentyTen,
and other boards based on the same header format.

Includes significant prototyping area using the spare shield area, and
supports Power-over-Ethernet (PoE) using either simple jumpers for DIY
PoE or a daughter-board module for full standards-compliant PoE.

Features:

 * Prototyping area.
 * 10/100Base-T connectivity.
 * Power-over-Ethernet "PD" (powered device) support.
 * Activity / status indicators.
 * Reset button wired through to Arduino reset pin.
 * Wiznet W5100 IC reset circuit.
 * SPI bus contention fixed for W5100 IC.
 * Parts overlay on both the top and the bottom.


More information is available on our product page at:

  http://www.freetronics.com/products/ethernet-shield

The "docs" folder within this repository includes a handy copy of the
schematic in PDF format and image(s) of the pcb.


INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer. Then open EAGLE and
navigate to Projects -> eagle -> EthernetShield.


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below.


LICENSE
-------
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL).
The "license" folder within this repository also contains a copy of
this license in plain text format.
