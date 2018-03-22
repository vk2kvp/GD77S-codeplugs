# GD77S-codeplugs
The codeplugs on this site have been designed for use with a GD77S (Note the S - this is the Standard version with no display and knob/button controls)

<b>CPS Version</b>: All the codeplugs here have been created and can be edited in MD77S CSP v1.0.7 which is available at http://s3.amazonaws.com/s3.image.ro/download/Software/Radioddity/GD-77/Software%20Radioddity%20GD-77S%20V1.1.7.zip

<b>Setup the codeplug for your personal use</b>  Before using this codeplug, you will need to:
 - Edit the "Radio ID" value to your DMR ID. Without this set correctly, the transceiver will not transmit on digital channels
 - Set the frequency of your hotspot to 439.175MHz (of edit the frequency for the HS channels in the codeplug to suit your hotspot frequency.
 - Repeaters channels and corresponging zones are inlcuded in the codeplug (identified in the codeplug filename). To change these values to suit your local repeater, edit the frequency value to suit and rename the zone as apptopriate. 

<b>VK1RMB+HS+CBv0x.dat</b> 4 Zones including an experimental zone for Australian UHF CB (receive only). Open the codeplug in CPS v1.0.7 and study the zones to see the channel numbers. Scan lists have been created corresponding to each of the four zones and an appropriate scan list is assigned to each channel. A brief description of the zones follows:
  - Zone 1: CB. A collection of UHF CB channels. When openning this codeplug in the CPS DO NOT open the Basic Information folder. This will reset the frequency range to 400-470MHz and clear all channel frequencies above 469MHz.
  - Zone 2: VK1RBM. The is the Canberra, Australia DMR-MARC repeater. Rename this zone to suit your local repeater, plus reset the frequencies for the corresponding channels to your repeater's frequency.
  - Zone 3: HS BM. Channels for Brandmeister talkgroups with a focus on Australian state based TGs
  - Zone 4: HS DRM. A selection of channels programmed with private TGs to connect DMR+ reflectors. CH8 is TG8 which is to be used to talk once the appropriate reflector is set with a 3 second transmit on one of the other channels.
