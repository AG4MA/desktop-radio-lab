# Build log

## 2026-10-25: project foundation

**Completed:** defined the amateur radio objective, the modular station concept and the sequence from receive only experiments to authorized transmission.

**Evidence:** the repository documentation. No physical station, measurements, reception or contacts are claimed.

**Open:** initial budget, antenna site, existing equipment, experience and licensing status.

**Next experiment:** select the first receive band and assemble a minimal receive chain after the starting point is recorded.

## 2026-10-25: compare objectives before purchases

**Completed:** documented proposed goals from lunar and satellite experiments to intercontinental HF voice, local VHF/UHF operation and first reception, with success criteria and implications for buying.

**Recommendation:** build toward HF voice contacts in Europe and on another continent, retain useful VHF/UHF capability, and validate original antenna and accessory builds. Advanced branches remain optional and unselected.

**Open:** owner priorities and the existing starting point inputs. No purchases, hardware builds or measurements were made.

## 2026-10-25: budgets and autonomous communication

**Completed:** added estimated total costs for each radio objective and three solar powered network options, with dated component price anchors, exclusions and an illustrative energy calculation.

**New requirement:** a base left in place on solar power and portable radios distributed to other people. The owner suggested city or flat countryside for estimation. Four portables are assumed for cost comparison only.

**Evidence limits:** no purchase, compatible cart, site survey, coverage test, energy measurement or radio authorization verification. The repeaters and direct radio kits are distinct architectures. Required distance and group size remain open; the owner asked for cost understanding before further specification.

## 2026-10-25: separate projects and correct the DIY cost framing

The next entries follow two separately tracked projects: the homemade HF station and the autonomous emergency network. The owner deprioritized lunar reflection and requested a stronger DIY emphasis. The commercial budget figures have been qualified and a documented low power HF kit candidate has been researched. No purchase or construction has occurred. See [workstreams](workstreams.md).

**Superseded:** the owner subsequently clarified that these are consecutive phases of one project, as recorded below.

## 2026-10-25: unify the project progression

**Confirmed direction:** build the homemade station first, progress to intercontinental HF contacts, then develop autonomous emergency stations using that experience. The HF station is an intermediate milestone. Lunar reflection remains parked.

**Language:** all GitHub content in English; conversation with the owner in Italian.

**Documentation change:** unified the goals and roadmap, added the later solar and network validation stages, and replaced default commercial receiver and transmitter choices with construction from documented circuits and selected components. Kits remain candidates, not selected purchases.

**Evidence limits:** no equipment bought, assembled or tested; no radio contacts or coverage claims. Four portable radios and a 72 hour test remain assumptions.

## 2026-10-25: assess step 1 costs and feasibility

**Completed:** assessed the initial homemade HF station phase and its smaller antenna and receiver milestone separately. Recommended constructing a documented single band circuit in measured increments. Added an explicit parts, iteration and basic tool allowance, and verified optional kit and tool price anchors.

**Planning figures:** EUR 300 to 550 for the station and EUR 150 to 350 for basic tools if needed. The smaller first receiver and antenna milestone targets EUR 120 to 200 in parts. Suitable RF measurement equipment is assumed borrowed; access is not confirmed. These are estimates, not a selected bill of materials or a spending commitment.

**Evidence limits:** no circuit or band selected, no purchases, no assembly or measurements. Antenna space, existing equipment and experience remain unknown. The later intercontinental and autonomous station milestones are unchanged. See [step 1 feasibility](step-1-feasibility.md).

## 2026-10-25: verify direct product prices

**Owner request:** provide direct product links rather than relying on broad budget calculations.

**Completed:** recorded product links, quantities, displayed prices, tax and shipping limitations. Four starter bench items total EUR 74.18 before shipping. This corrects any implication that the earlier EUR 150 to 350 allowance was a necessary minimum. Radio kits are priced as optional alternatives, with missing power, audio and antenna dependencies identified.

**Evidence limits:** the full component built radio still has no selected and priced bill of materials. The original whole station and first receiver allowances are unverified estimates. No order, assembly or hardware test was made. See [direct product evidence](product-price-check.md).

## 2026-10-26: quote the standalone HF voice build

**Owner requirement:** assemble a radio for receiving and transmitting voice at long distance without a PC during normal use. The owner tentatively proposed the roof for the antenna. Its usable span, attachments and feed-line route remain unknown.

**Completed:** prepared a [current proposed bill of materials](standalone-hf-bom.md) using the QMX kit built for 9 V, a compatible microphone kit, headphones, operating supply, dummy load, antenna/choke kits and bench equipment. Verified electrical interfaces against manufacturer manuals, corrected the previous soldering tool choice, and identified initial firmware installation as a one-time computer dependency. Prices retain their actual currencies and tax qualifications.

**Evidence limits:** this is kit assembly with factory-fitted SMD parts, not a fully original component design. No products were ordered or tested. Shipping, import treatment, roof installation, tool access and independent RF measurements are not fully costed. Published part subtotals are not a delivered station total. Intercontinental HF and autonomous emergency communication remain future milestones.

**Next physical inputs:** roof dimensions and cable route, existing tool inventory and commissioning access. Complete the installation plan and delivered quote before site-dependent purchasing.

## 2026-10-26: add the scientific RF geolocation objective

**Owner request:** include the ability to locate other transmitting stations using radio waves for scientific experiments.

**Completed:** added an [experiment plan](rf-geolocation.md) and linked it to the objectives and roadmap. The plan separates RF measurements from validation coordinates, starts with controlled direction finding, and requires position errors, uncertainty and unsuccessful results to be reported. TDOA and HF skywave localization are later investigations.

**Evidence limits:** documentation only. No geolocation receiver, antenna array, synchronization system or processing platform has been selected, purchased or tested. No accuracy or additional cost is claimed. The standalone HF proposal and main project progression remain in place.

## Entry template

Copy this template for each experiment. Retain failed experiments when they explain the next decision.

| Field | Record |
| --- | --- |
| Date and objective | What capability or problem is being tested? |
| Baseline | Previous configuration and expected outcome |
| Equipment and parts | Models, quantities, actual costs and reused items |
| Build | Diagram, dimensions, photos and relevant code |
| Procedure | Connections, settings, frequency, mode and conditions |
| Results | Observations, measurements and linked evidence |
| Limitations | Calibration, uncertainty and uncontrolled variables |
| Decision | Keep, revise or reject the change, with a reason |
| Next step | One concrete experiment |
