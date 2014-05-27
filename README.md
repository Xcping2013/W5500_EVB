# W5500 EVB
=========

- W5500 chip development platform for **net'enabled** microcotroller applications
- Ethernet (W5500 Hardwired TCP/IP chip) and 32-bit ARM® Cortex™-M0 based designs
- Arduino Pin-compatible platform hardware

For more details, please refer to [W5500 EVB page](http://wizwiki.net/wiki/doku.php?id=products:w5500:w5500_evb) in WIZnet Wiki.

## Features
- WIZnet W5500 Hardwired TCP/IP chip
  - Hardwired TCP/IP embedded Ethernet controller
  - SPI (Serial Peripheral Interface) Microcontroller Interface
  - Hardwired TCP/IP stack supports TCP, UDP, IPv4, ICMP, ARP, IGMP, and PPPoE protocols
  - Easy to implement of the other network protocols
- NXP LPC11E36/501 MCU (LPC11E36FHN33)
  - 32-bit ARM® Cortex™-M0 microcontroller running at up to 50MHz
  - 96kB on-chip flash / 12kB on-chip SRAM / 4kB on-chip EEPROM / Various peripherals
- On-board Temperature sensor / Potentiometer
- Pin-compatible with Arduino Shields designed for the UNO Rev3
- Ethernet / USB-mini B connector and 10-pin Cortex debug connector for SWD(Serial Wire Debug)

<!-- W5500 EVB pic -->
![W5500 EVB](http://wizwiki.net/files/-.jpg "W5500 EVB")

<!-- W5500 EVB pinout -->
![W5500 EVB Pinout](http://wizwiki.net/files/-.jpg "W5500 EVB Pinout")

## Software
These are libraries source code and example projects based on LPCXpresso IDE.

Requried Libraries are as below.
- lpc_chip_11exx (NXP LPC11exx serise chip driver)
- wiznet_evb_w5500evb_board (WIZnet W5500 EVB board library)
- ioLibrary (WIZnet W5500 EVB ethernet library and protocols)

Example projects are as below.
- Basic demos (LED blinky and loopback test)
- DHCP client
- DNS clinet
- On-board Temperature sensor
- On-board Potentiometer

## Hardware material, Documents and Others
Various materials are could be found at [W5500 EVB page](http://wizwiki.net/wiki/doku.php?id=products:w5500:w5500_evb) in WIZnet Wiki.
- Documents
  - Getting Started: Hello world! / Downloading a new program
  - Make New W5500 EVB Projects
- Technical Reference
  - Datasheet
  - Schematic
  - Partlist
  - Demension
- See also



## Revision History
First release : Jun. 2014