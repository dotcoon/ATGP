# Kenwood TH-D72 - APRS Digipeater

## Draft

DRAFT MODE - 03-06-2022

Content within table needs to be reviewed for completeness and accuracy.

### Overview

While it is possible to use programming software such as Kenwood MCP-4A or RT Systems KRS-D72  to apply the configuration settings listed below, we encourage you to program the settings via the front-panel keypad. While the process is tedious, it is important to ensure you are able to configure your radio in the field without a computer at your disposal.

Once your radio is configured, the end result will allow you to operate as follows:

VFO A: 144.340 MHz - APRS enabled (AT Golden Packet APRS frequency*)

VFO B: 445.925 MHz - Voice communications with adjacent stations

* *DO NOT USE THE STANDARD APRS frequency 144.390 MHz for AT Golden Packet!*

### Firmware Update

Update your radio's firmware with the most current version available on the Kenwood support site:

https://www.kenwood.com/i/products/info/amateur/software_download.html

The most current version for the Kenwood TH-D72A as of the time this document was posted is: 1.10 (released August 2020)

### Configuration Backup and Factory Reset

Prior to configuring your radio, make a backup of the configuration and perform a factory reset. This will ensure that you start with the factory default configuration as your baseline.

The easiest method of backing up the configuration is with Kenwood MCP-4A or RT Systems KRS-D72.

Once you have a good backup, proceed to performing a factory reset. 

There are two methods to perform a factory reset:

#### Option 1

1. Turn the tranceiver power off
2. Press [F] + Power On
3. Use the Up/Down arrows or rotate the Tuning control until "Full Reset" is selected
4. Press **> OK** to set the reset type
5. Press > OK again to perform the reset

#### Option 2

1. Navigate to Menu 199 
2. Choose FULL RESET from the menu



### Configuration Settings

| Menu | Display                   | Details                                                      |
| ---- | ------------------------- | ------------------------------------------------------------ |
| 300  | My Callsign               | Set *MYCALL* to tactical call (**MDMTN-7**)                  |
| 360  | * 1                       | Select **Position 1** - *ensure this position is selected with ** |
| 361  | Name                      | Enter name for site (i.e **MDMTNS-7**) - *up to 8 characters* |
| 362  | N (S)                     | Latitude Entry                                               |
| 363  | E (W)                     | Longitude Entry                                              |
| 370  | Speed                     | Set to **DISABLED**                                          |
| 371  | Altitude                  | Set to **DISABLED**                                          |
| 372  | Pos. Ambiguity            | **DISABLED**                                                 |
| 380  | Position Comment          | **SPECIAL**                                                  |
| 390  | *1/TX Rate/Text           | Select ***1**, Set TX Rate to **1/1**, and TEXT to *your call* and *name* |
| 3A0  | QSY in Status             | Set to **ON**                                                |
| 3A1  | Tone/Narrow               | Set to **OFF**                                               |
| 3A2  | Shift/Offset              | Set to **OFF**                                               |
| 3C0  | Icon/Symbol               | Set station icon to **DIGIPEATER** (optionally **TENT** or **HUMAN**) |
| 3C1  | Symbol                    |                                                              |
| 3C2  | Table                     |                                                              |
| 3D0  | Method                    | TX Beacon set to **AUTO**                                    |
| 3D1  | Initial Interval          | **10 Minutes** (will likely start more frequently and decrease as we go) |
| 3E0  | Decay Algorithm           | Set to **OFF**                                               |
| 3E1  | Prop. Pathing             | Set to **OFF**                                               |
| 3H0  | Type                      | Select **OTHERS** (ensure you use * to ACTIVATE!)            |
| 3H1  | Wide1-1/Relay/ABBR/Others | Set to **HOP7-7,HOP7-7** (confirm value with coordinator)    |
| 3H2  | Total Hops                | ????????                                                     |
| 3K0  | Digipeat(MyCall)          | Set to **ON**                                                |
| 3L0  | Time (UI Check Time)      | **15 Seconds** (Default is 28)                               |
| 3M0  | UIdigi                    | Set to **OFF**                                               |
| 3N0  | UIflood                   | Set to **ON**                                                |
| 3N1  | Alias                     | Set to **HOP**                                               |
| 3N2  | Substitution              | Set to **ID**                                                |
| 3O0  | UItrace                   | Set to **ON**                                                |
| 3O1  | Alias                     | Set to **TEMP**                                              |
| 3U0  | Display Area              | Set to **ENTIRE ALWAYS**                                     |
| 3U1  | Interrupt Time            | Set to **10 Seconds**                                        |

NOTE: There are quite a few options available throughout the APRS configuration settings. If they are not covered in the aforementioned table, leave them set to the default value(s)



### Field Operations

Once out in the field, the recommended method involves:

1. Tune the radio on VFO A to 144.340 MHz - Set the power level on VFO A to High (if your battery has sufficient power) - otherwise, use Medium power
2. Tune the radio on VFO B to 444.925 MHz - Use minimum power for voice operations
3. Press the TNC button until D and APRS12 are displayed on the top line of the display
4. Press the BCON button until BCON is also displayed on the top line of the display.
