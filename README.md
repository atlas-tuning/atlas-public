# Atlas
Atlas is a free, open-source ECU calibration application made for reverse-engineering and recalibrating modern vehicles. This project started as an effort to better understand the behavior of the 2022 WRX ECU but, as there is a lack of free and maintained tooling for software engineers and auto enthusiasts to gain first-party access to their ECUs, has since pivoted towards adopting a much broader feature set that encourages modern ECU research, recalibration and modification.

![Atlas 2024.1](https://github.com/atlas-tuning/atlas/blob/main/java/screenshots/atlas2.png?raw=true "Atlas 2024.1 running on MacOS")

## WARNING!

There are several disclaimers worth stating, in regards to your use of Atlas:
* Messing with your ECU is dangerous. You can "brick" or permenantly ruin an ECU by improperly instructing it to perform routines or flashing incompatible calibrations. The project recommends that users consult with a professional mechanic or tuner before making any ECU modifications. Use of the project's software tools is at the user's own risk.
* Improperly modifying your ECU calibration (Target Boost, Ignition Timing, Mass Airflow Calibration, Wastegate Duty Cycle, Rev Limiter, Volumetric Efficiency, etc.) can directly damage your vehicles engine. This project and its contributors will not be held responsible for any damage to the engine or other vehicle components that may result from the use of these tools. Modifying a car's ECU tune can be complex and risky, and should only be attempted by experienced users.
* In many cases, ECU access can lead to exposing calibrations for regulated systems such as emissions-related features of a vehicle. This project will not provide definitions to recalibrate any legally regulated systems (TGV, EGR, P0420, etc.). By using Atlas, you agree to use Atlas in a legal manner that abides by all laws local to you regarding these systems and their regulated calibration.

## Get Involved
Atlas is in active development. If you're interested in getting involved in the effort to make ECU reverse engineering and recalibrating modern vehicles free and accessible, consider dropping by the Atlas [Discord server](https://discord.gg/XVVm3DhJPd)!

## Features
### Comprehensive Tuning Suite:
* Enables in-depth ECU research, leading to full recalibration capabilities
* Supports multiple platforms, including Windows, macOS (including M-series), and Linux (including SteamOS and Raspbian), leveraging Java and open-source libraries
* Integrates the Ghidra SRE Framework bundle to analyze tables and emulate ROM machine code

### Versatile Connectivity:
* Supports the Tactrix OpenPort 2.0 via direct serial/COM connection with a natively-written driver in Atlas

### Advanced Visualization and Editing:
* Provides 2D and 3D OpenGL visualizations for gauges, tables, and function charts
* Offers a 1-2 dimension table editor with common arithmetic functions for efficient calibration editing
* Includes a live table definition interface to manage project tables and expedite table definition
* Features a value scaling configuration UI to rapidly create new scaling operations as they are identified within ECU logic

### Comprehensive Documentation and Diagnostics:
* Allows customization of memory parameters to notate ECU RAM offsets corresponding to specific metrics (e.g., RPM, Requested Torque, etc.)
* Provides a simple node graph to create and browse documentation of ECU behavior
* Includes gauges and a data logger for calibration diagnostics and troubleshooting, with project configuration and CSV export capabilities

### Streamlined Project Management:
* Offers a composite project system that consolidates all calibrations and ECU configurations in a single file
* Features an intelligent table-matching system to automatically detect new tables and discover existing tables in unknown variants
* Enables a consistent experience across model years and variants with an intelligent calibration cross-application function

## Support

### Supported Hardware: J2534 (CAN)

| Device               | MacOS     | Windows   | Linux/ <br>SteamOS | Android     |
|----------------------|-----------|-----------|---------------|-------------|
| [Tactrix OpenPort 2.0](https://www.tactrix.com/index.php?page=shop.product_details&flypage=flypage.tpl&product_id=17&category_id=6&option=com_virtuemart&Itemid=53&redirected=1&Itemid=53) | ![Supported](https://badgen.net/badge/color/Supported/green?label=) | ![Supported](https://badgen.net/badge/color/Supported/green?label=) | ![Supported](https://badgen.net/badge/color/Supported/green?label=) | ![In Progress](https://badgen.net/badge/color/In%20Progress/blue?label=) |

### Supported Vehicles:

| Make   | Model     | Year      | Market | MT          | CVT     |
|--------|-----------|-----------|--------|-------------|---------|
| Subaru | WRX       | 2024      | USDM   | ![In Progress](https://badgen.net/badge/color/In%20Progress/blue?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru | WRX       | 2024      | AUDM   | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru | WRX       | 2023      | USDM   | ![In Progress](https://badgen.net/badge/color/In%20Progress/blue?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru | WRX       | 2023      | AUDM   | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru | WRX       | 2022      | USDM   | ![Supported](https://badgen.net/badge/color/Supported/green?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru | WRX       | 2022      | AUDM   | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru<br>Toyota | BRZ<br>GR86       | 2022+     | USDM   | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru | WRX STi   | 2015-2021 | USDM   | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Subaru | WRX       | 2015-2021 | USDM   | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Toyota | NXP-based | 2022+     | USDM   | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
| Honda  | NXP-based | 2022+     | USDM   | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |

### Supported Maps

If a map area is supported, that does not mean it is complete, but that it is exposed well enough to tune for common applications such as confidently adding more horsepower, modifying your idle, gear ranges, etc.

| Family     | Ignition | Airflow  | Fueling     | Idle     | Gear     |
|------------|----------|----------|-------------|----------|----------|
| Subaru WRX | ![Supported](https://badgen.net/badge/color/Supported/green?label=) | ![Supported](https://badgen.net/badge/color/Supported/green?label=) | ![In Progress](https://badgen.net/badge/color/In%20Progress/blue?label=) | ![Supported](https://badgen.net/badge/color/Supported/green?label=) | ![Supported](https://badgen.net/badge/color/Supported/green?label=) |
| Subaru BRZ<br>Toyota GR86 | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) | ![Planned](https://badgen.net/badge/color/Planned/purple?label=) |
  
## Emissions Statement

* Atlas is open-source software intended for the legal and responsible modification of a vehicle’s ECU calibration. It is essential that users of Atlas adhere strictly to emissions regulations to ensure compliance with all applicable laws and maintain the viability of this community resource.
* Atlas does not condone, support, or facilitate the removal or tampering of any emissions-regulated components from a vehicle. This includes, but is not limited to, components such as the Exhaust Gas Recirculation (EGR) system, Tumble Generator Valve (TGV), and catalytic converters.
* Atlas is committed to operating within the bounds of U.S. emissions laws and regulations as set forth by the Environmental Protection Agency (EPA) and other relevant authorities. The removal or modification of emissions-regulated components is strictly prohibited under the Clean Air Act, as well as other pertinent federal laws, including but not limited to:

> - The Clean Air Act (42 U.S.C. § 7401 et seq.)
> - National Emission Standards for Hazardous Air Pollutants (NESHAP) (42 U.S.C. § 7412)
> - Motor Vehicle Air Pollution Control Act (42 U.S.C. § 7521 et seq.)
> - Energy Policy Act (42 U.S.C. § 13201 et seq.)

* Non-compliance with these legal requirements could jeopardize the existence of Atlas and other similar open-source projects. Atlas is dedicated to enabling vehicle enthusiasts to tune their vehicles responsibly, ensuring both environmental responsibility and full legal compliance. Users are urged to familiarize themselves with and adhere to all relevant emissions regulations to support the continued success and legality of Atlas.
* By using Atlas, you agree to comply with all applicable emissions regulations and acknowledge that any illegal modifications to emissions-controlled components are strictly prohibited.


## License
Atlas is licensed under the [Affero General Public License (AGPL) version 3.0](https://www.gnu.org/licenses/agpl-3.0.en.html). The AGPL 3.0 license was chosen to allow engineers and tuners to modify the Atlas source code and add functionality, without requiring proprietary information (tunes/calibrations) to be shared. This is done to encourage the use of Atlas by commercial entities to sell calibrations to customers, as long as all emissions laws and local laws are followed. The goal is to provide the automotive community with a wide range of tools to support their work, while ensuring that the numerous trade secrets in the commercial tuning market are not further encouraged by Atlas.
