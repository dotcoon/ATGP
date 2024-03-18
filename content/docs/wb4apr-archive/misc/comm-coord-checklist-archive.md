#  Golden Packet Comm Coordination Checklist

Last modified: Feb. 12, 2022

From aprs.org website dated: July 7, 2016

Below is a set of things that may make an operation during the ATGP
event more successful and/or more enjoyable.


## Lessons Learned

- Importance of 2nd HT on 144.39 for receiving ANSRVR announcements
- Temporarily turn off `INTERRUPT` display to see your D710 digi
- New 5m `BCON` rate at Springer, Katahdin, & GD Hill.  All others 10m
- 4 AH batery plus a spare seems to be enough for a 3 hour event
- Minimize messages and if used, use `BLN#XXX`'s to avoid `ACKS`
- Communicate status by updating your status when things change

## Overall Checklist

1. Camera: Take a camera and a book.  Book is in case all work 100%.

2. Signal Mirror: For signalling other peaks in view as part of the
Boy Scouts Operation On-Target or any other cooperating target. (Is
this still something that's happening?  Have not heard of Boy Scout
coordination lately.)

3. ARRL Pamphlets: Take ham rdio hand-out pamphlets for onlookers

4. APRS HT:  **(required)** Use a 2nd APRS radio (HT) to maintain
APRS text communications with the designated Shack Potato and all
other stations using normal APRS on 144.390 MHz.  Use the root
callsign of your station without any SSID.  Begin using it as you
leave home! Periodically send status updates to ANSRVR with 1st
words: "CQ AT ..."

See http://aprs.org/ansrvr.html (Will need an updated link).  The
dual band APRS HT can also be used to monitor your local published
voice repeater.  Use EL power or long RG58 coax and a beam to the
nearest digi to minimize self-QRM to your primary operations on
144.34 MHz.

5. BATTERY: You will need about 4 AHrs.  Take two to have a main
and a spare.  And give you a half-way indiciation when the first
one is out.

6. 144.340 MHz DIGIPEATER:  Set up your D7xx APRS digipeater radio
BAND-A on 144.340 MHz and set the volume so you can hear what is
going on on the channel.  This channel is shared with Balloons and
ATV, so we want to be aware of any conflicts, and hear how the
packets are souding...

7. BAND-B on 445.925 MHz CTCSS 100: Use BAND-B on 445.925 MHz
simplex for voice coordination to adjacent sites.  This avoids QRM
on the 2 meter event band!  This is important!  Also a VOICE-RELAY
around a failed APRS mountain top will still count.

8. SETTINGS: Set up your radio as a HOPn-N and TEMPn-N digipeater
operating in APRS mode.  The D710's can all be set from the front
panel, but a PC is required for the initial setup of the D700
prior to the event, but is not required during operations.  This
digipeater radio will be used only for the 144.340 MHz DIGI, for
APRS DIGI beacons (status text updated as needed) and for voice
UHF coordination on 445.925 MHz voice.  See radio settings:

D700_settings

** TURN OFF any AUTO-REPLY MESSAGES in digipeater radio!**

9. DUPLICATES:  The D7XX has a bug that will cause your own station
to digipeat its OWN packet a second time.  Fortuntately the other
digipeaters will not, because they will see that second one as a dupe.
We just live with this quirk (and it does slightly improve success).

10. LOGGING: If possible, have a second APRS receive-only station
running APRS on the event channel with a PC for logging all packets.
This station can be left unattended down at the car or at home since
it can hear all packets from your station's digi.  Do not let it
beacon on the event channel!  Even once...too much QRM.

11. COORDINATION/STATUS: Use your mobile (enroute) or your APRS HT
(note 4 above), to be in communication
