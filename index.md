# USB-C Ham Radio Roundup

This list is intended to inform ham/shortwave radio buyers about the available USB-C radios in the market and what their compatibility/quirks may be, and be perpetually updated by the community at-large.

There have been good & bad implementations of USB-C brought to market and this table summarizes the basic facts about each USB-C port.

# USB-C Radios Tested
| Radio Product Name  | Vendor | USB-C Charging? | USB-C Data? | Notes | Reference/Source |
| ------------- | ------------- | ------------- | ------------- | ------------- | -------------|
| AT-878UV USB-C Battery | Anytone  |  Yes. Only with USB-A to USB-C cable! | No | Naughty! No USB-C Sink terminations, cannot use USB-C-only cables and chargers. | Tested by wojo @ HRCC Discord
| UV-K5  | Quansheng  |  Yes. Only with USB-A to USB-C cable! | No | Naughty! No USB-C Sink terminations, cannot use USB-C-only cables and chargers. | Tested by KK7LXU 
| RB17V | Retevis  |  Yes. Only with USB-A to USB-C cable! | No | Naughty! No USB-C Sink terminations, cannot use USB-C-only cables and chargers. | Tested by KJ6LNN 
| TD-H3 | TIDRADIO  |  Yes. Only with USB-A to USB-C cable! | No | Naughty! No USB-C Sink terminations, cannot use USB-C-only cables and chargers. | Tested by wojo @ HRCC Discord 
| TD-H8 (Gen 1) | TIDRADIO  |  Only with USB-A to USB-C cable! | No | Naughty! No USB-C Sink terminations, cannot use USB-C-only cables and chargers. | Tested by KK7LXU 
| TD-H8 (Gen 2) | TIDRADIO  |  Only with USB-A to USB-C cable! | No | Naughty! No USB-C Sink terminations, cannot use USB-C-only cables and chargers. | Tested by KK7LXU
| X6100 | XIEGU  |  No. | 2x USB-C data (USB2) ports: Host & Device | Naughty! USB Device port has no USB-C Sink termination, cannot use USB-C-only cables. USB Host port untested. | Tested by KK7LXU


## How to Help
Have or know about a USB-C radio not on the list? We want to know if works properly! Feel free to modify and submit Pull Request with any new radio product info.

### What you need:
1) A known-good USB-C to USB-C cable
2) A USB-C wall-wart charger/powerbank (with a USB-C receptacle)
3) A USB-C radio

### How to test USB-C Charging:
1) Connect your known-good USB-C/USB-C  cable to your USB-C charger
2) Connect your USB-C radio to the USB-C/USB-C cable.
3) Does the radio charge? If so, indicate Yes in the USB-C Charging column. Else, indicate No.

### How to test USB-C Data:
1) Connect your known-good USB-C/USB-C data cable to a PC/laptop's USB-C data port.
2) Connect your USB-C radio to the USB-C/USB-C cable. (Some radios have multiple USB ports, ensure it is connected to the USB Device port)
3) Does the radio enumerate/register as a USB device on your PC/laptop? If so, indicate Yes in the USB-C Data Column. Else, indicate No.
