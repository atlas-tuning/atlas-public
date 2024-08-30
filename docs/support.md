---
layout: page
title: Support Info
tagline: Detailed adapter and vehicle support information
permalink: /support.html
ref: support
order: 1
---

## Supported Adapters

Atlas supports the following adapters and hardware through custom cross-platform device drivers that are built directly into Atlas. The listed adapters should work out of the box with no additional configuration required.

| Device               | Platform (Desktop) | Platform (Mobile) | Connection | Type | Flash Speed<br>(Average) |
|----------------------|--------------------|-------------------|------------|------|--------------------------|
| [Tactrix OpenPort 2.0](https://www.tactrix.com/index.php?page=shop.product_details&flypage=flypage.tpl&product_id=17&category_id=6&option=com_virtuemart&Itemid=53&redirected=1&Itemid=53)* | ![Supported](https://badgen.net/badge/icon/Supported?icon=windows&label=Windows&color=green)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=apple&label=Mac%20OS%20X&color=green)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=terminal&label=Linux/SteamOS&color=green)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=terminal&label=Linux/Ubuntu&color=green)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=terminal&label=Linux/Debian&color=green)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=terminal&label=Linux/Arch&color=green) | ![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=googleplay&label=Android&color=blue)<br>![Unsupported](https://badgen.net/badge/icon/Unsupported?icon=apple&label=iOS&color=red) | Wired<br>(USB-Mini B) | OpenPort | 3~5 minutes |
| [OBDLink MX+](https://www.obdlink.com/products/obdlink-mxp/) | ![Supported](https://badgen.net/badge/icon/Supported?icon=windows&label=Windows&color=green)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=apple&label=Mac%20OS%20X&color=green)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=terminal&label=Linux/SteamOS&color=green) | ![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=googleplay&label=Android&color=blue)<br>![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=apple&label=iOS&color=blue) | Wireless<br>(Bluetooth 3.0) | STN | 6~9 minutes |
| [OBDLink LX](https://www.obdlink.com/products/obdlink-lx/) | ![Supported](https://badgen.net/badge/icon/Supported?icon=windows&label=Windows&color=green)<br>![Testing](https://badgen.net/badge/icon/Testing?icon=apple&label=Mac%20OS%20X&color=purple)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=terminal&label=Linux/SteamOS&color=green) | ![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=googleplay&label=Android&color=blue)<br>![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=apple&label=iOS&color=blue) | Wireless<br>(Bluetooth 3.0) | STN | 10~11 minutes |
| [OBDLink EX](https://www.obdlink.com/products/obdlink-ex/) | ![Supported](https://badgen.net/badge/icon/Supported?icon=windows&label=Windows&color=green)<br>![Testing](https://badgen.net/badge/icon/Testing?icon=apple&label=Mac%20OS%20X&color=purple)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=terminal&label=Linux/SteamOS&color=green) | ![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=googleplay&label=Android&color=blue)<br>![Unsupported](https://badgen.net/badge/icon/Unsupported?icon=apple&label=iOS&color=red) | Wired<br>(USB-A) | STN | 6~9 minutes |
| [OBDLink SX](https://www.obdlink.com/products/obdlink-sx/) | ![Supported](https://badgen.net/badge/icon/Supported?icon=windows&label=Windows&color=green)<br>![Testing](https://badgen.net/badge/icon/Testing?icon=apple&label=Mac%20OS%20X&color=purple)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=terminal&label=Linux/SteamOS&color=green) | ![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=googleplay&label=Android&color=blue)<br>![Unsupported](https://badgen.net/badge/icon/Unsupported?icon=apple&label=iOS&color=red) | Wired<br>(USB-A) | STN | 6~9 minutes |
| [Veepeak OBDCheck BLE+](https://www.amazon.com/dp/B076XVQMVS) | ![Testing](https://badgen.net/badge/icon/Testing?icon=windows&label=Windows&color=purple)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=apple&label=Mac%20OS%20X&color=green)<br>![Testing](https://badgen.net/badge/icon/Testing?icon=terminal&label=Linux/SteamOS&color=purple) | ![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=googleplay&label=Android&color=blue)<br>![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=apple&label=iOS&color=blue) | Wireless<br>(Bluetooth LE) | ELM327 | 30~60 minutes |

Atlas is always interested in expanding support to new adapters and hardware. If you have a device you'd like to see supported and isn't listed here, please check our current [hardware requests](https://github.com/atlas-tuning/atlas-public/labels/hardware%20request) on GitHub and see if a ticket already exists for the device in question. If one doesn't exist yet, consider opening a new [adapter or hardware request](https://github.com/atlas-tuning/atlas-public/issues/new?labels=hardware%20request&template=adapter_request.md&title=).

## Supported Vehicles

If a vehicle is supported, it may not be complete. Please report any missing tables or desired exposed tables to our GitHub project as a new [issue](https://github.com/atlas-tuning/atlas/issue).

| Make   | Model<br>(Chassis) | Year      | Varient |
|--------|--------------------|-----------|---------|
| Subaru | WRX (VB)     | 2024      | ![In Progress](https://badgen.net/badge/icon/In%20Progress?label=USDM%20-%206MT&color=blue)<br>![Planned](https://badgen.net/badge/icon/Planned?label=AUDM%20-%206MT&color=purple)<br>![Planned](https://badgen.net/badge/icon/Planned?label=USDM%20-%20CVT&color=purple)<br>![Planned](https://badgen.net/badge/icon/Planned?label=AUDM%20-%20CVT&color=purple) |
| Subaru | WRX (VB)     | 2023      | ![Supported](https://badgen.net/badge/icon/Supported?label=USDM%20-%206MT&color=green)<br>![Planned](https://badgen.net/badge/icon/Planned?label=AUDM%20-%206MT&color=purple)<br>![Planned](https://badgen.net/badge/icon/Planned?label=USDM%20-%20CVT&color=purple)<br>![Planned](https://badgen.net/badge/icon/Planned?label=AUDM%20-%20CVT&color=purple) |
| Subaru | WRX (VB)     | 2022      | ![Supported](https://badgen.net/badge/icon/Supported?label=USDM%20-%206MT&color=green)<br>![Planned](https://badgen.net/badge/icon/Planned?label=AUDM%20-%206MT&color=purple)<br>![Planned](https://badgen.net/badge/icon/Planned?label=USDM%20-%20CVT&color=purple)<br>![Planned](https://badgen.net/badge/icon/Planned?label=AUDM%20-%20CVT&color=purple) |
| Subaru | WRX (VA)     | 2015-2021 | ![In Progress](https://badgen.net/badge/icon/In%20Progress?label=USDM%20-%206MT&color=blue)<br>![Planned](https://badgen.net/badge/icon/Planned?label=USDM%20-%20CVT&color=purple) |
| Subaru | WRX STi (VA) | 2015-2021 | ![Planned](https://badgen.net/badge/icon/Planned?label=USDM%20-%206MT&color=purple) |
| Subaru<br>Toyota | BRZ (ZD8)<br>GR86 (ZN8) | 2022+     | ![In Progress](https://badgen.net/badge/icon/In%20Progress?label=USDM%20-%206MT&color=blue)<br>![Planned](https://badgen.net/badge/icon/Planned?label=USDM%20-%206AT&color=purple) |
| Toyota | NXP-based | 2022+     | ![Planned](https://badgen.net/badge/icon/Planned?label=5/6MT&color=purple)<br>![Planned](https://badgen.net/badge/icon/Planned?label=Auto&color=purple) |
| Honda  | NXP-based | 2022+     | ![Planned](https://badgen.net/badge/icon/Planned?label=5/6MT&color=purple)<br>![Planned](https://badgen.net/badge/icon/Planned?label=Auto&color=purple) |

## Issues/Troubleshooting

Atlas is a relatively new software project, and while we strive to provide an easy to use and trouble-free product, errors may still arise. In this event, users are urged to check our currently [known issues](https://github.com/atlas-tuning/atlas/labels/bug). If this is a new issue, please [open a support ticket](https://github.com/atlas-tuning/atlas-public/issues/new?labels=bug&template=bug_report.md) on our GitHub or drop by the [Atlas Community on Discord](https://atlasopensource.org/discord.html).

[Go to the Home Page]({{ '/' | absolute_url }})
