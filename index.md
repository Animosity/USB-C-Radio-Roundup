
# USB-C Ham Radio Roundup

This list is intended to inform ham/shortwave radio buyers about the available USB-C radios in the market and what their compatibility/quirks may be, and be perpetually updated by the community at-large.

There have been good & bad implementations of USB-C brought to market (most radios still can't charge from proper USB-C cables and chargers!) and this table summarizes the basic facts about each radio's USB-C ports. 
# Updates
* July 12 2024 - Added Baofeng UV-17R via KE9BAH, added ID-50 result via K5VOL
* July 10 2024 - Added Baofeng UV-9R results via K5RNL
* July 9 2024 - Added Yintalk Quansheng-compatible battery results via K5RNL
* July 8 2024 - Updated TIDRADIO TD-H3 results (USB C-to-C charging confirmed!) via KI5WDN
* July 3 2024 - initialized list with 15 radios
  
# USB-C Radios Tested
| Radio Product Name                                   | Vendor        | USB A-to-C Charging?                 | USB C-to-C Charging? | USB-C Data?                                     | Notes                                                                                                           |                 Reference/Source                           |
|-|-|-|-|-|-|-|
| (Battery) QB-44HL USB-C Battery for AT-878UV/DMR-6X2 | Anytone/BTECH | Yes                                  | INCOMPATIBLE!        | No                                              | Naughty! No USB-C Sink resistors, INCOMPATIBLE with USB-C cables and chargers.                                  | Tested by wojo @ HRCC Discord                    |          |
| UV-5RH PRO MAX                                       | Baofeng       | Yes                                  | Yes (5V)                  | No                                              | Nice! This radio works correctly. Battery model# BL-5RH.                                                        | Tested by VK3PGO                                 |          |
| UV-9R                                       | Baofeng       | Yes                                  | Yes (5V)                  | No                                              | Nice! This radio works correctly. Battery model# BL-9.           | Tested by K5RNL 
| UV-17R                                      | Baofeng       | Yes                                  | INCOMPATIBLE!                | No                                              |Naughty! No USB-C Sink resistors, INCOMPATIBLE with USB-C cables and chargers. Battery model# RL-17            | Tested by KE9BAH
| (Mod) IC-705 KD9LJF USB-C/SEND Control Board Upgrade | KD9LJF (Icom) | Yes                                  | Yes (5V)                 | Yes - USB2 Device port.                         | Nice! COMPATIBLE with USB-C cables and chargers.                                                                | User Manual reference only                       |          |
| ID-50A                                               | Icom          | Yes | Yes (5V)        | Yes - USB2 Device port.                         | Nice! This radio works correctly. COMPATIBLE with USB-C cables and chargers.                                                                           | Tested by K5VOL                      |          |
| HG-UV98                                              | LanchonLH     | Yes                                  | INCOMPATIBLE!        | UNTESTED TBD         | No                                                                                                 | UNTESTED                                         | UNTESTED |
| (Battery) UV-K5/K6/K58/5R 7.4V@3500mAh                    | Yintalk (Quansheng-compatible)     | Yes                                  | Yes (5V)       | N/A                                              | Nice! This battery's connector works correctly.                                  | Tested by K5RNL (Product Link: https://www.aliexpress.us/item/3256807133512324.html)                                |          |
| UV-K5                                                | Quansheng     | Yes                                  | INCOMPATIBLE!        | No                                              | Naughty! No USB-C Sink resistors, INCOMPATIBLE with USB-C cables and chargers.                                  | Tested by KK7LXU                                 |          |
| UV-K5(8)                                             | Quansheng     | Yes | INCOMPATIBLE!        | No                                              | Naughty! No USB-C Sink resistors, INCOMPATIBLE with USB-C cables and chargers.                                  | Inferred by design similarity to Quansheng UV-K5 |          |
| UV-K6                                                | Quansheng     | Yes | INCOMPATIBLE!        | No                                              | Naughty! No USB-C Sink resistors, INCOMPATIBLE with USB-C cables and chargers.                                  | Inferred by design similarity to Quansheng UV-K5 |          |
| RA79                                                 | Retevis       | Yes | INCOMPATIBLE!        | No                                              | Naughty! No USB-C Sink resistors, INCOMPATIBLE with USB-C cables and chargers.                                  | Inferred by design similarity to Quansheng UV-K5 |          |
| RB17V                                                | Retevis       | Yes | INCOMPATIBLE!        | No                                              | Naughty! No USB-C Sink resistors, INCOMPATIBLE with USB-C cables and chargers.                                  | Tested by KJ6LNN                                 |          |
| TD-H3                                                | TIDRADIO      | Yes | Yes (5V)        | No                                              | Nice! This radio works correctly. Battery model# BP-3. Chargers tested: [anker 5045su2000225, nekteck pd100u-1tga, onn wiablu100075576, mycharge rzqc128v-a]                                | Tested by KI5WDN                     |          |
| TD-H8 (Gen 1)                                        | TIDRADIO      | Yes      | INCOMPATIBLE!        | No                                              | Naughty! No USB-C Sink resistors, INCOMPATIBLE with USB-C cables and chargers.                                  | Tested by KK7LXU                                 |          |
| TD-H8 (Gen 2)                                        | TIDRADIO      |Yes      | INCOMPATIBLE!        | No                                              | Naughty! No USB-C Sink resistors, INCOMPATIBLE with USB-C cables and chargers.                                  | Tested by KK7LXU                                 |          |
| X6100                                                | XIEGU         | N/A - Barrel plug charger                                  | N/A - Barrel plug charger                 | Yes - 1 USB2 Host port &amp; 1 USB2 Device port | Naughty! USB Device port has no USB-C Sink resistors, INCOMPATIBLE with USB-C cables. USB Host port untested. | Tested by KK7LXU                                 |          |
| X6200                                                | XIEGU         | N/A - Barrel plug charger                                  | N/A - Barrel plug charger                 | Yes - 1 USB2 Host port &amp; 1 USB2 Device port | UNTESTED TBD                                                                                                    | UNTESTED                                         |          |


## How to Help
Have or know about a USB-C radio not on the list? We want to know if works properly! Feel free to modify and submit Pull Request with any new radio product info, or just drop the information into an Issue (https://github.com/Animosity/USB-C-Radio-Roundup/issues)

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
