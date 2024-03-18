# ARCHIVE: AT Golden Packet - Kenwood TH-D72 - APRS Digipeater Settings

Robert Bruninga's original document dated:

28 July 2011
Updated - February 18, 2020


These are the instructions for setting up the TH-D72 handheld as a lightweight carry-up-to the mountain top DIGIPEATER:  If you are not a digipeater, but a hiker, then use your usual settings (except for path).

All of the digipeater settings for a D72 can be made from the Menu:

Press F key and then TUNING knob
Select APRS menu

300 BASIC settings set MYCALL to MDMTN-7
360 MY POSITION - enter lat long and make sure that the 
    ASTERIX is associated with this #1 memory selection.   
    Do that with the * button when that memory is selected
370 Turn off Speed, Altitude and ambiguity
380 Set comment to SPECIAL
390 Select *1, set TX rate to 1/1 and TEXT to ur call and name
3A0 Set QSY in Status to ON.  Set Tone and Shift to off
3C0 set station icon to DIGIPEATER (otherwise use the Human or Tent)
3D0 TX Beacon to AUTO and Interval 10 minutes
3E0 Algorithm, set Decay OFF and Proportional OFF
3H0 PATH
    TYPE *OTHERS <-remember to use the * key to activate!
    PATH: HOP7-7,HOP7-7
3K0 DIGIPEAT (MYCLL) ON
3M0 UIdigipeat set to OFF
3L0 UICHECK TIME 15 seconds (default is 28)
3N0 UIFLOOD ON
    ALIAS HOP
    SUBSTITUTION ID
3O0 UITRACE ON
    ALIAS TEMP
3U0 Display Area = Entire-Always, Interrupt time 10 sec

TUNE RADIO ON BAND A to 144.34 MHz
TUNE RADIO ON BAND B to 445.925 MHz
Set A to HIGH power if your battery can afford it.  
Otherwise use Medium Power.  Use minimum voice power on side B as required.

PRESS TNC button until "D" and "APRS12" should show on the top of SIDE A

PRESS "BCON" button until BCON displays on the top line of the display.

That should be it.  Please test from another radio using the path of HOP7-7 and be sure it digipeats.

Bob, WB4APR