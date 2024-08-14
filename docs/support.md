# Detailed Support Information
## Supported Adapters

Atlas supports the following adapters and hardware through custom cross-platform device drivers that are built directly into Atlas. The listed adapters should work out of the box with no additional driver installation required.

| Device               | Platform (Desktop) | Platform (Mobile) | Connection | Type | Flash Speed<br>(Average) |
|----------------------|--------------------|-------------------|------------|------|--------------------------|
| [Tactrix OpenPort 2.0](https://www.tactrix.com/index.php?page=shop.product_details&flypage=flypage.tpl&product_id=17&category_id=6&option=com_virtuemart&Itemid=53&redirected=1&Itemid=53) | ![Supported](https://badgen.net/badge/icon/Supported?icon=windows&label=Windows&color=green)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=apple&label=Mac%20OS%20X&color=green)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=terminal&label=Linux/SteamOS&color=green)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=terminal&label=Linux/Ubuntu&color=green)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=terminal&label=Linux/Debian&color=green)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=terminal&label=Linux/Arch&color=green) | ![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=googleplay&label=Android&color=blue)<br>![Unsupported](https://badgen.net/badge/icon/Unsupported?icon=apple&label=iOS&color=red) | Wired<br>(USB-Mini B) | OpenPort | 3~5 minutes |
| [OBDLink MX+](https://www.obdlink.com/products/obdlink-mxp/) | ![Testing](https://badgen.net/badge/icon/Testing?icon=windows&label=Windows&color=purple)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=apple&label=Mac%20OS%20X&color=green)<br>![Testing](https://badgen.net/badge/icon/Testing?icon=terminal&label=Linux/SteamOS&color=purple) | ![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=googleplay&label=Android&color=blue)<br>![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=apple&label=iOS&color=blue) | Wireless<br>(Bluetooth 3.0) | STN | 6~9 minutes |
| [OBDLink LX](https://www.obdlink.com/products/obdlink-lx/) | ![Testing](https://badgen.net/badge/icon/Testing?icon=windows&label=Windows&color=purple)<br>![Testing](https://badgen.net/badge/icon/Testing?icon=apple&label=Mac%20OS%20X&color=purple)<br>![Testing](https://badgen.net/badge/icon/Testing?icon=terminal&label=Linux/SteamOS&color=purple) | ![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=googleplay&label=Android&color=blue)<br>![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=apple&label=iOS&color=blue) | Wireless<br>(Bluetooth 3.0) | STN | Unmeasured |
| [OBDLink EX](https://www.obdlink.com/products/obdlink-ex/) | ![Testing](https://badgen.net/badge/icon/Testing?icon=windows&label=Windows&color=purple)<br>![Testing](https://badgen.net/badge/icon/Testing?icon=apple&label=Mac%20OS%20X&color=purple)<br>![Testing](https://badgen.net/badge/icon/Testing?icon=terminal&label=Linux/SteamOS&color=purple) | ![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=googleplay&label=Android&color=blue)<br>![Unsupported](https://badgen.net/badge/icon/Unsupported?icon=apple&label=iOS&color=red) | Wired<br>(USB-A) | STN | Unmeasured |
| [Veepeak OBDCheck BLE+](https://www.amazon.com/dp/B076XVQMVS) | ![Testing](https://badgen.net/badge/icon/Testing?icon=windows&label=Windows&color=purple)<br>![Supported](https://badgen.net/badge/icon/Supported?icon=apple&label=Mac%20OS%20X&color=green)<br>![Testing](https://badgen.net/badge/icon/Testing?icon=terminal&label=Linux/SteamOS&color=purple) | ![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=googleplay&label=Android&color=blue)<br>![In Progress](https://badgen.net/badge/icon/In%20Progress?icon=apple&label=iOS&color=blue) | Wireless<br>(Bluetooth LE) | ELM327 | 30~60 minutes |

Atlas is always interested in expanding support to new adapters and hardware. If you have a device you'd like to see supported and isn't listed here, please check our current [hardware requests](https://github.com/atlas-tuning/atlas-public/labels/hardware%20request) on GitHub and see if a ticket already exists for the device in question. If one doesn't exist yet, consider opening a new [adapter or hardware request](https://github.com/atlas-tuning/atlas-public/issues/new?labels=hardware%20request&template=adapter_request.md&title=).

## Supported Vehicles

If a vehicle is supported, it may not be complete. Please report any missing tables or desired exposed tables to our GitHub project as a new [issue](https://github.com/atlas-tuning/atlas/issue).

| Make   | Model     | Year      | Market | MT          | CVT     |
|--------|-----------|-----------|--------|-------------|---------|
| Subaru | WRX       | 2024      | USDM   | ![In Progress](https://badgen.net/badge/color/In%20Progress/blue?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru | WRX       | 2024      | AUDM   | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru | WRX       | 2023      | USDM   | ![Supported](https://badgen.net/badge/color/Supported/green?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru | WRX       | 2023      | AUDM   | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru | WRX       | 2022      | USDM   | ![Supported](https://badgen.net/badge/color/Supported/green?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru | WRX       | 2022      | AUDM   | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru<br>Toyota | BRZ<br>GR86       | 2022+     | USDM   | ![In Progress](https://badgen.net/badge/color/In%20Progress/blue?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru | WRX STi   | 2015-2021 | USDM   | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru | WRX       | 2015-2021 | USDM   | ![In Progress](https://badgen.net/badge/color/In%20Progress/blue?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Toyota | NXP-based | 2022+     | USDM   | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Honda  | NXP-based | 2022+     | USDM   | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |

## Supported Maps

If a map area is supported, that does not mean it is complete, but that it is exposed well enough to tune for common applications such as confidently adding more horsepower, modifying your idle, gear ranges, etc.

| Family     | Ignition | Airflow  | Fueling     | Idle     | Gear     |
|------------|----------|----------|-------------|----------|----------|
| Subaru WRX | ![Supported](https://badgen.net/badge/color/Supported/green?label=) | ![Supported](https://badgen.net/badge/color/Supported/green?label=) | ![In Progress](https://badgen.net/badge/color/In%20Progress/blue?label=) | ![Supported](https://badgen.net/badge/color/Supported/green?label=) | ![Supported](https://badgen.net/badge/color/Supported/green?label=) |
| Subaru BRZ<br>Toyota GR86 | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |

## Issues/Troubleshooting

Atlas is a relatively new software project, and while we strive to provide an easy to use and trouble-free product, errors may still arise. In this event, users are urged to check our currently [known issues](https://github.com/atlas-tuning/atlas/labels/bug). If this is a new issue, please [open a support ticket](https://github.com/atlas-tuning/atlas-public/issues/new?labels=bug&template=bug_report.md) on our GitHub or drop by the [Atlas Community on Discord](https://discord.gg/XVVm3DhJPd).

[Back](./index.html)
