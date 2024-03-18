# ARCHIVE: Golden Packet D700 portable DIGI CONFIGURATION

Last modified: Feb. 12, 2022

13 June 2021 - Removed FTM350 from this file, since it does not digi!
21 July 10   - Separated out the D710 data to its own file
22 July 09   - Original file for 2009

Originally written by:
Bob, WB4APR


The fundamental requirements for a temporary Golden Packet Digi are:

- Support HOPn-N paths (with 1 level of trace history)
- Support TEMPn-N paths with tracing
- Position beacon once every 10 minutes via `HOP7-7,HOP7-7` (mainline stn)
- Position beacon once every 10 minutes via `TEMP2-2` (alternative solution)
- **DO NOT** support WIDEn-N

Next is a quick summary of things to configure on your Kenwood D700.  **NOTE: you**
**will need a PC connection, so configure these radios BEFORE the day of**
**the event!!!**  A set-by-set instructions follow the quick summary.

## Station Functions Set From Front Panel Menu

- Enter `MYCALL` for your site (for example, `COMERS-4`)
- Enter latitude/longitude (`LAT/LON POSITION`) for your site
- Set to beacon once every 10 minutes
- Using the path of HOP7-7,HOP7-7 (mainline)

## Station Functions Set from PC Port
 
- Set `MYCALL` for your site plus `SSID`
- Set `BTEXT` !DDMM.mmN/DDDMM.mmW;comments
- Set `UNPROTO` APGOLD VIA `HOP7-7,HOP7-7`
- Set `BEACON` every `60` (that's 10 minutes)
- Set `UIFLOOD` to `HOP,ID`
- Set `UITRACE` to `TEMP`
- Set `HID` to `OFF`


## AT Golden Packet Event Digipeater Settings for the D700

1. **PRIOR TO THE EVENT,** make these TNC settings in PACKET mode using
a dumb terminal.  These settings can remain permanently in the
radio and it can still be used normally on the normal APRS channel
or it can be used for Field Day or the Annual AT event or any
other emergency where HOPn-N or TEMPn-N paths are used.

- Set `UIFLOOD` to `HOP,ID`
- Set `UITRACE` to `TEMP`
- Set `HID` to `OFF`

If you are going to operate the radio in APRS mode, then all the rest
of the setting you make in APRS mode.  But if you are going to operate
in PACKET mode, you have to also set the `BTEXT`, `UNPROTO`, and
`BEACON TNC` commands listed earlier if they are not provided by any
client APRS software.

2. Power cycle radio and then test the digipeater with another radio
using `HOP7-7`.  It should digipeat, and substitute its own call
(`MYDIGI`) and decrement the N number.  The digipeated path should look
like this:  `W3XYZ>APRSAT,MYDIGI,HOP7-6:.......

3. For the event, then set APRS mode and these MENU items:
- `RADIO - DISPLAY` - `KEY FUNCTION MODE3` (D700 only)
- `RADIO - MEMORY`  - `AUTO PM STORE OFF`  (D700)
- `AUX   - AUTO PM STORE OFF`              (D710, maybe this is not needed on this page?)
- `APRS  - MYCALL`  - To your assigned station call-SSID
- `APRS  - GPS UNIT` - `OFF`
- `APRS  - MY POS`  - Set to your assigned position, see web page)
- `APRS  - STATION ICON` - Set to digipeater star
- `APRS  - STATUS TEXT` - Set as required, but keep it short!)
- `APRS  - STATUS TX RATE` - Set to `1/1`
- `APRS  - PACKET PATH` - `HOP7-7,HOP7-7` (Mainline, TEMP2-2 if alternate needed)
- `APRS  - PACKET TX` - `AUTO`
- `APRS  - TX INTERVAL` - `10 minutes`

Again, if operating `PACKET` mode, then you have to also set up the
`TNC BTEXT`, `BEACON`, and `UNPROTO` commands if not done by any client
software.

4. `BAND-A` set to 144.34 MHz, volume up, DATA channel, SQL tight!

5. `BAND-B` set to 445.925 MHz or other simplex voice frequency

6. `FUNCTION - PM-IN` - `PM#`  Save this for rapid configuration.

7. Cycle `F` function button (including holding 1 sec) until you get
the TNC button on the lower left.  Cycle it until you get the APRS
TNC isplay in the upper left of the display.

8. Cycle `F` button to find the `BCON` button, and cycle it until
`BCON` display on the top line of the display to enable beacons.

Operating procedures will be in a different file: AT-checklist.txt
