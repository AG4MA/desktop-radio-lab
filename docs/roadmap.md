# Build roadmap

All hardware milestones are pending. The owner selected one progression: homemade construction, intercontinental HF contacts, then autonomous emergency stations. The [project path](workstreams.md) explains the sequence and DIY priorities. Adapt implementation details to evidence while preserving this order.

The [step 1 feasibility study](step-1-feasibility.md) costs the whole initial station phase and its smaller first antenna and receiver build separately. Its allowances do not represent a selected parts list or completed hardware.

| Stage | Work | Completion evidence | Status |
| --- | --- | --- | --- |
| 0. Define the starting point | Inventory equipment and skills; set a first phase budget; assess antenna space; establish licensing status | Written constraints, first target band and a justified initial parts list | Pending owner inputs |
| 1. Antenna and first receiver | Build a feasible antenna and receive chain from a documented circuit or modules | Schematic, dimensions, assembly photos and repeatable reception | Planned |
| 2. Characterize reception | Measure behavior; improve placement, feed line or filtering when evidence justifies it | Controlled comparison with settings and limitations recorded | Planned |
| 3. Build the HF transmitter | Assemble and test the required signal generation, modulation, amplification and filtering stages; evaluate documented kits where appropriate | Circuit and bench checks into a suitable load, with output and unwanted emissions checked using appropriate equipment | Planned |
| 4. Integrate the station | Add controls, enclosure, low voltage distribution, antenna matching and receiver protection | A reproducible working configuration and demonstrated controls | Planned |
| 5. First HF contacts | Verify operating authorization and commission the station on the chosen bands | Initial contact log and station configuration | Planned |
| 6. Intercontinental HF milestone | Improve antenna and operating practice using evidence | A documented intercontinental voice contact with the homemade station | Planned |
| 7. Autonomous power prototype | Measure station consumption and build the solar and battery system for the intended later site | Logged energy use, charging behavior and a defined autonomy test | Planned after HF milestone |
| 8. Reproducible network stations | Select the appropriate radio service and topology; build the fixed station and provision compatible user radios | Reproducible parts list, diagrams, verified operator and station prerequisites, and bench integration | Planned after HF milestone |
| 9. Emergency network validation | Test communication at agreed locations and without external power; verify unattended behavior where applicable | Coverage records, endurance measurements and operating instructions | Planned after integration |

Choose the later network's bands and equipment for its actual coverage needs. The first HF radio need not become the local repeater. Four user radios and 72 hours of autonomy are provisional costing and test assumptions. Lunar reflection is parked, and satellite work is not selected.

## Parallel scientific experiment: RF geolocation

The owner requested [RF geolocation](rf-geolocation.md) on 2026-10-26. It can begin after repeatable reception and a suitable measurement setup are available. It is an additional experiment, not a prerequisite for the numbered stages above.

| Experiment step | Completion evidence | Status |
| --- | --- | --- |
| Define and build the measurement setup | Selected reference signal, band, receiver geometry, antenna design and calibration procedure, with a verified parts list | Planned; hardware and costs open |
| Demonstrate direction finding | Repeatable bearing observations of a known reference transmitter, with errors and ambiguities recorded | Not started |
| Estimate position from multiple observations | Reproducible position estimates compared against separately held ground truth; uncertainty and failed estimates included | Not started |
| Assess advanced methods | A feasibility report for synchronized TDOA and, separately, HF skywave propagation; implementation only after the required equipment and model are established | Future investigation |

The current standalone HF bill of materials does not include a validated geolocation setup. Normal HF voice operation remains independent of a PC; computation for this experiment still needs its own design decision.

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
