---
layout: page
title: FAQ
tagline: Frequently Asked Questions
permalink: /faq.html
ref: faq
order: 3
---

### Where can I download Atlas?
* Atlas is currently under active development and is not presently available for download.

### How much does Atlas cost?
* Atlas will release as free software. 

### What does Atlas run on?
* Atlas is a Java based, multiplatform application, currently being actively developed for Microsoft Windows, Apple Mac OS X and various flavors of Linux including SteamOS, Arch and Debian. 

### When will Atlas be available?
* A release date has not been set in stone. Many features are still in development and rigorous testing accompanied along with thorough pre-release documentation needs to be completed before we publish a general release. That said, we feel that late 2024 is a realistic goal. 

### Does Atlas support the VA WRX? (2014-2021)
* Although Atlas originally began as a tool intended to support the VB (2022+) chassis WRX, it’s scope has recently expanded and development is currently in progress for the FA20 powered VA chassis (2014-2021) WRX. More information can be found on our [support page](http://atlasopensource.org/support.html). 

### What do I need to connect Atlas to my car?
* Development began with the Tactrix OpenPort 2.0 and Atlas fully supports this adapter with a built-in application driver. STN based devices such as the OBDLink MX+ are currently being tested with other varients soon to follow. With some restrictions, ELM327 based devices also support flashing and datalogging. More detailed information can be found on the [support page.](http://atlasopensource.org/support.html) 

### Can I use an ELM327 adapter with Atlas?
* ELM327 based devices with firmware version 2.1 or greater are supported in Atlas with a built-in driver. Flashing via this method takes significantly longer than others. (30-60 minutes as opposed to 3-5 minutes via a Tactrix OpenPort 2.0)

### Can I download and modify my OTS or ProTune?
* Atlas does not and will not support any ECU calibration (tune) loaded via a Cobb AccessPort. If you want to use Atlas on a vehicle married to an AccessPort, you’ll need to unmarry the AccessPort and revert to your stock calibration in order to begin using Atlas.

### Can I turn off my check engine light  with Atlas?
* Suppression of non-emissions related diagnostic trouble codes is fully supported. Disabling or tampering with emissions related systems (to include DTCs) is explicitly not supported. Please see our [emissions statement](http://atlasopensource.org/emissions.html) for more information.


[Go to the Home Page]({{ '/' | absolute_url }})
