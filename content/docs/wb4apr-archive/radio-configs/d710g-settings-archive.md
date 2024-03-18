# ARCHIVE: AT Golden Packet - Kenwood TM-D710G - APRS Digipeater Settings

Robert Bruninga's original document dated:

7 July 2016

All of the digipeater settings for a D710G can be made from the front panel.  Here are the settings:

Remember the Tuning knob is also the SELECT button for navigating menus.

Press F key and then TUNING knob
Select APRS menu

600	BASIC settings set MYCALL to MDMTN-7
601	Set A band for APRS data and 1200 (later 9600)
602	GPS port INPUT OFF
605	MY POSITION - enter lat long and make sure that the ASTERIX is associated with this #1 memory selection. Do that with the USE button when that memory is selected
606	Set speed off
607	Set SPECIAL
608	*1 enter text:  Change this frequently to show your status
609	Position limit OFF
610	Station icon: select the TENT (Portable)
611	Beacon TX algorithm
METHOD  Auto
Initial interval 10 minutes
Decay OFF
Proportional OFF
612	PATH
TYPE * OTHERS  (be sure to press USE button to get asterisk *)
PATH: HOP7-7,HOP7-7
613	APRS
614	Voice Alert OFF
616	DIGIPEAT (MYCALL) ON
617	UICHECK TIME 10 seconds (default is 28)
618	UIDIGI OFF
619	UIFLOOD ON
ALIAS HOP
SUBSTITUTION ID
620	UITRACE ON
ALIAS TEMP
622	AUTO REPLY MESSAGE OFF!!!
625	INTERRUPT ALWAYS

TUNE RADIO ON BAND A to 144.34 MHz
TUNE RADIO ON BAND B to 445.925 MHz

Set A to HIGH power if your battery can afford it. Otherwise use Medium Power.  Use minimum voice power on side B as required.  Keep the DATA band squelch tight.

PRESS TNC button (lower right) until "D" shows on band A "APRS12" should show on the top of SIDE A

PRESS "BCON" button until BCON displays on the top line of the display.

That should be it.  Please test from another radio using the path of HOP7-7 and be sure it digipeats.

PM - PROGRAM MEMORIES:  Save everything in a PM memory as follows:
Once everything above is programmed:
1) Press FUNCTION - PMin - Select PM number.  I use #5
2) Now *important*, SELECT PM#5 to operate from
3) NOW there are additional menu options in various menu items
4) go to AUX and make two more settings:
   900 Set the NAME of your PM to AT-GP
   922 Set Auto-PM-store to OFF !!!!!!!

NOW THEN DO ANOTHER [F] - PMin - 5 to SAVE this in PM5.

Power off the radio and back on and it should come up in PM5. RE-SAVE the PM.

Operating from a PM and having AUTO-PM-STORE - OFF will assure that nothing you will do will mess up PM 5 unless you purposefully make changes and then do another [F] - PMin - 5 SAVE.

Bob, WB4APR