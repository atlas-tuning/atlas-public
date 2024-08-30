---
layout: page
title: FAQ
tagline: Frequently Asked Questions
permalink: /faq.html
ref: faq
order: 3
---

### Where can I download Atlas?
* Atlas is in [closed beta](https://atlasopensource.org/2024/08/30/limited-beta.html) and is not presently available for download.

### How much does Atlas cost?
* Atlas is free software. 

### What does Atlas run on?
* Atlas is a Java based, multiplatform application, currently being developed for Microsoft Windows, Apple Mac OS X and various flavors of Linux including SteamOS, Arch and Debian. 

### When will Atlas be available?
* Atlas is currently in a [limited Beta](https://atlasopensource.org/2024/08/30/limited-beta.html). Rigorous testing accompanied with thorough pre-release documentation needs to be completed before we can publish a general release. That said, we feel that early to mid Autumn 2024 is a realistic goal. 

### Does Atlas support the VA WRX or STI? (2015-2021)
* Although Atlas originally began as a tool intended to support the VB (2022+) chassis WRX, it’s scope has recently expanded and development is currently in progress for the FA20 powered VA chassis (2015-2021) WRX. More information can be found on our [support page](http://atlasopensource.org/support.html). 

### What do I need to connect Atlas to my car?
* Atlas fully supports the Tactrix OpenPort 2.0 and STN based adapters such as the OBDLink MX+ with a built-in application driver. With some restrictions, ELM327 based devices also support flashing and datalogging. More information and a detailed list of supported devices can be found on our [support page.](http://atlasopensource.org/support.html) 

### Can I use an ELM327 adapter with Atlas?
* ELM327 based devices with firmware version 2.1 or greater are supported in Atlas with a built-in driver. Flashing via this method takes significantly longer than others. (30-60 minutes as opposed to 3-5 minutes via a Tactrix OpenPort 2.0)

### Can I download and modify my OTS or ProTune?
* Atlas does not and will not support any ECU calibration (tune) loaded via a Cobb AccessPort. If you want to use Atlas on a vehicle paired to an AccessPort, you’ll need to unpair the AccessPort and revert to your stock calibration in order to begin using Atlas.

### Can I use my existing AccessPort with Atlas?
* Due to the security features implemented on the device, a Cobb AccessPort cannot be used in conjunction with Atlas to flash new calibrations, change maps, view gauges or datalog.

### Can I turn off my check engine light with Atlas?
* Suppression of non-emissions related diagnostic trouble codes is fully supported. Disabling or tampering with emissions related systems (to include DTCs) is explicitly not supported. Please see our [emissions statement](http://atlasopensource.org/emissions.html) for more information.


[Go to the Home Page]({{ '/' | absolute_url }})
