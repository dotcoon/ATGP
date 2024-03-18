# ARCHIVE: AT Golden Packet - Kenwood TM-D710 - APRS Digipeater Settings

Robert Bruninga's original document dated:

20 July 2012
Updated 18 February 2020

All of the digipeater settings for a D710 can be made from the front panel.  Here are the settings:

Remember the Tuning knob is also the SELECT button for navigating menus.

Press F key and then TUNING knob
Select APRS menu

600 BASIC settings set MYCALL to MDMTN-7
602 GPS port INPUT OFF
605 MY POSITION - enter lat long and make sure that the ASTERIX is associated with this #1 memory selection.   
Do that with the USE button when that memory is selected
608 *1 enter text:  "unattended" (without quotes)
610 station icon: select the TENT (Portable)
611 Beacon TX algorithm
    METHOD  Auto
    initial interval 10 minutes
    Decay OFF
    Proportional OFF
612 PATH
    TYPE OTHERS
    PATH: HOP7-7,HOP7-7

IMPORTANT. Select OTHERS and press USE button to make sure it will actually use this method type...  A "*" will show by *OTHERS to show that it will be used.  This is easy to overlook

616 DIGIPEAT (MYCALL) ON
617 UICHECK TIME 10 seconds (default is 28)
619 UIFLOOD ON
    ALIAS HOP
    SUBSTITUTION ID
620 UITRACE ON
    ALIAS TEMP

TUNE RADIO ON BAND A to 144.34 MHz
TUNE RADIO ON BAND B to 445.925 MHz

Set A to HIGH power if your battery can afford it.  
Otherwise use Medium Power.  Use minimum voice power on side B as required.  Keep the DATA band squelch tight.

PRESS TNC button (lower right) until "D" shows on band A "APRS12" should show on the top of SIDE A

PRESS "BCON" button until BCON displays on the top line of the display.

That should be it.  Please test from another radio using the path of HOP7-7 and be sure it digipeats.

PM - PROGRAM MEMORIES:  If you want to save all this into a PM memory so that it is not lost or screwed up in the field, save it into a PM.  But be SURE that you  have 

521 AUX AUTO-PM-STORE OFF

This selection only shows up in the AUX menu when you have a PM selected.  This setting is saved in each PM, so that you can have some PM's that can be changed on the fly and some that once programmed cannot get screwed up unless you specifically RE-SAVE the PM.

Bob, Wb4APR