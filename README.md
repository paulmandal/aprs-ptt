# APRS PTT Project

The purpose of this project is to implement a PTT circuit for a Baofeng HT that integrates with APRSDroid.  This will reduce the amount of time required to send an APRS packet to something not obnoxious such that sending a packet to the repeater on the ISS won't stomp on other sender's transmisisons.

Breaking this down into parts:

- Design and implement PTT circuit
- Modify APRSDroid to trigger the PTT circuit during transmission of a packet
- Build a directional antenna suited for the APRS frequency in order to contact the ISS repeater