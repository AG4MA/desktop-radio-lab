# Build roadmap

All hardware milestones are pending. The order can adapt to the available antenna site and equipment, while retaining the final amateur radio objective.

Use the [objective comparison](objectives.md) to decide the intended station capability before the parts list. The proposed stretch goals are optional branches, not additional mandatory stages.

| Stage | Work | Completion evidence | Status |
| --- | --- | --- | --- |
| 0. Define the starting point | Inventory equipment and skills; set a first phase budget; assess antenna space; establish licensing status | Written constraints, first target band and a justified initial parts list | Pending owner inputs |
| 1. First reception | Set up one SDR, compatible software and a basic antenna | Repeatable local reception, settings and a spectrum screenshot or permitted sample | Planned |
| 2. First original antenna | Build and install a simple antenna suited to the chosen band | Drawing, dimensions, parts, photos and baseline comparison | Planned |
| 3. Improve reception | Identify noise or overload; test antenna placement, feed line or one filter | Controlled comparison and measured benefit or documented lack of benefit | Planned |
| 4. Build desk controls | Add an encoder, controls and firmware to operate the receiver | Schematic, firmware and a working demonstration | Planned |
| 5. Prepare transmission | Complete the required authorization; select HF and VHF/UHF equipment in justified increments; prepare power, antenna matching and receiver protection | Verified operating prerequisites and documented bench setup | Planned |
| 6. First contacts | Commission the transmit chain and complete initial amateur contacts on selected bands | Station configuration and contact log | Planned |
| 7. Distant HF contact | Improve the HF antenna and operating practice using measured evidence | A documented distant contact and an explanation of propagation and station conditions | Planned |

VHF/UHF can provide an early operating milestone once authorized. HF is the planned primary route toward distant contacts. Adding a digital mode, satellite operation or another band is a later extension with its own requirements.

## Starting point worksheet

| Input | Current value |
| --- | --- |
| Initial budget, including antenna and cable | Unknown |
| Antenna location: room, balcony, roof or other | Unknown |
| Usable antenna dimensions and feed line route | Unknown |
| Existing radio equipment and tools | Not inventoried |
| Computer and available USB connections | Not inventoried for this project |
| Soldering and electronics experience | Unknown |
| Amateur licence, callsign and authorization | Not verified |
| First receive band and mode | Not selected |

Keep private documents and the precise home address out of the public repository. The public worksheet only needs the technical constraints.

## Measurement approach

Compare one change at a time. Record frequency, mode, receiver gain, bandwidth, antenna position and time. Use repeated or interleaved observations to distinguish an improvement from propagation changes. Uncalibrated SDR levels are relative observations, not calibrated power measurements.

An antenna analyzer or VNA can characterize matching after calibration at the measurement plane. A good match alone does not prove radiation efficiency or greater range. Record insertion loss and rejection for a filter when suitable equipment is available.

Before connecting a transmitter to an antenna, use an appropriately rated dummy load and measurement setup to check the selected equipment. Verify power, unwanted emissions and compliance as applicable; a dummy load does not replace authorization. SDR inputs require isolation and attenuation appropriate to the actual transmitter power.
