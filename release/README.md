# ArduPilot Project
This branch will show the ARDUPILOT RSSI OSD ELEMENT as XX.YYY.ZZZ (RFmode.LQ.RSSI in dBm).
make spaces on the right side of the RSSI OSD element so that your RSSI display is not cropped.

click on the FC firmware you need, and then right click on the download button and save link as. and set:

RSSI_TYPE = 3 (ReceiverProtocol)
this custom firmware will show the OSD RSSI ELEMENT as XX.YYY.ZZZ (RFmode.LQ.RSSI in dbm). it will also bypass the ardupilot crossfire serial number check, that causes a notication message to keep popping up (CRSF: RFmode is x, rate is xx).

this branch is based on the ardupilot 4.1 develop which I have flown with and tested. this branch base will only be updated when ardupilot 4.1 beta has been stable or released so that this branch minimize the risk of anything happening due to new features in the beta branch.
