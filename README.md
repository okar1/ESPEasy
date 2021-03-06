Click to open youtube video

[![Blynk integration demo](https://img.youtube.com/vi/5_V_DibOypE/0.jpg)](https://www.youtube.com/watch?v=5_V_DibOypE "Blynk integration demo")


|Latest Nightly  | Build Status | Docs | Patreon | Ko-Fi | PayPal |
|-------|-------|-------|-------|-------|-------|
| [![GitHub version](https://img.shields.io/github/release/letscontrolit/ESPEasy/all.svg)](https://github.com/letscontrolit/ESPEasy/releases/latest) | [![Build Status](https://travis-ci.org/letscontrolit/ESPEasy.svg?branch=mega)](https://travis-ci.org/letscontrolit/ESPEasy) | [![Documentation Status](https://readthedocs.org/projects/espeasy/badge/?version=latest)](https://espeasy.readthedocs.io/en/latest/?badge=latest) | [![donate](https://img.shields.io/badge/donate-Patreon-blue.svg)](https://www.patreon.com/GrovkillenTDer) | [![donate](https://img.shields.io/badge/donate-KoFi-blue.svg)](https://ko-fi.com/grovkillentder) | [![donate](https://img.shields.io/badge/donate-PayPal-blue.svg)](https://www.paypal.me/espeasy) |

For ways to *support* us, see [this announcement on the forum](https://www.letscontrolit.com/forum/viewtopic.php?f=14&t=5787), or have a look at the [Patreon](https://www.patreon.com/GrovkillenTDer), [Ko-Fi](https://ko-fi.com/grovkillentder) or [PayPal](https://www.paypal.me/espeasy) links above.

# In this fork of ESPEASY (see "some-my" branch):
* improved dummy plugin with keeping values permanently, even on device reboot
* Added OpenTherm plugin connecting ESP8266 to OpenTherm boiler device.
(now testing with OT hardware adapter http://ihormelnyk.com/opentherm_adapter and BOSCH Gas 6000 boiler)

# Original ESPEasy description follows...

# ESPEasy (development branch)


Introduction and wiki: https://www.letscontrolit.com/wiki/index.php/ESPEasy#Introduction

**MEGA**
:warning:This is the development branch of ESPEasy. All new untested features go into this branch. If you want to do a bugfix, do it on the stable branch, we will merge the fix to the development branch as well.:warning:

Next stable branch: https://github.com/letscontrolit/ESPEasy/tree/v2.0  (bug fixes only, since oct 2017))

Check here to learn how to use this branch and help us improving ESPEasy: http://www.letscontrolit.com/wiki/index.php/ESPEasy#Source_code_development


## Automated binary releases

Every night our build-bot will build a new binary release: https://github.com/letscontrolit/ESPEasy/releases

The releases are named something like 'mega-20180102' (last number is the build date)

Depending on your needs, we release different types of files:

Firmware name                                 | Hardware                | Included plugins            |
----------------------------------------------|-------------------------|-----------------------------|
ESPEasy_mega-20180102_normal_ESP8266_1024.bin  | ESP8266 with 1Mb flash  | Stable                      |
ESPEasy_mega-20180102_test_ESP8266_1024.bin    | ESP8266 with 1Mb flash  | Stable + Test               |
ESPEasy_mega-20180102_dev_ESP8266_1024.bin     | ESP8266 with 1Mb flash  | Stable + Test + Development |
ESPEasy_mega-20180102_normal_ESP8266_4096.bin  | ESP8266 with 4Mb flash  | Stable                      |
ESPEasy_mega-20180102_test_ESP8266_4096.bin    | ESP8266 with 4Mb flash  | Stable + Test               |
ESPEasy_mega-20180102_dev_ESP8266_4096.bin     | ESP8266 with 4Mb flash  | Stable + Test + Development |
ESPEasy_mega-20180102_normal_ESP8285_1024.bin  | ESP8285 with 1Mb flash  | Stable                      |
ESPEasy_mega-20180102_test_ESP8285_1024.bin    | ESP8285 with 1Mb flash  | Stable + Test               |
ESPEasy_mega-20180102_dev_ESP8285_1024.bin     | ESP8285 with 1Mb flash  | Stable + Test + Development |

## More info

Details and discussion are on the Experimental forum: https://www.letscontrolit.com/forum/viewforum.php?f=18

Automated builds of the (new) documentation can be found at [ESPEasy.readthedocs.io](https://espeasy.readthedocs.io/en/latest/)
