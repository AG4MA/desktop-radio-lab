# Step 1: homemade HF station, costs and feasibility

Assessed on 2026-10-25. This is a planning study, not a selected bill of materials or a purchase. All physical milestones remain pending.

Here, **step 1 means the first homemade station phase**: antenna, receiver, transmitter and controls. Its first smaller milestone is antenna plus receiver, corresponding to stage 1 in the [detailed roadmap](roadmap.md). Intercontinental contacts and the later autonomous emergency stations remain subsequent goals.

## Recommended scope

Build a single band SSB voice station in the 5 W class from a documented, proven circuit. Assemble and check the receive path first, then transmission, filters, switching and controls. The target output is provisional and must be measured. Select the actual band and circuit after checking antenna space and the available bench equipment.

The [BITX40 circuit description](https://www.hfsignals.com/index.php/bitx40-circuit-description/) provides a concrete example of an understandable SSB architecture with a published schematic and circuit explanations. It is a design reference, not a selected board purchase or a verified reproduction parts list. Building from components and documented circuits fits the owner's goal better than beginning with an original multiband design.

Buy semiconductors, suitable magnetic cores, wire, connectors and PCB materials. Build the circuits, wind the specified coils and transformers, make the antenna, and assemble the enclosure and controls. Buy a suitable isolated low voltage power supply; the construction scope begins on its low voltage side.

## Cost of the complete first station

These are our provisional gross spending allowances in EUR, not vendor quotations. They assume a simple wire antenna, modest cable length, a low power single band circuit, an existing computer where needed, and access to borrowed RF measurement equipment. Component availability, PCB sourcing, shipping, tax treatment and redesign can change the result. No paid construction labour is included.

| Item | EUR allowance | Construction scope |
| --- | --- | --- |
| Antenna, feed line and connectors | 50 to 90 | Wire antenna, simple supports and feed arrangement; no professional roof work |
| Receiver, transmitter, oscillator, filters and controls | 120 to 220 | Components and PCB materials for a documented circuit; no complete commercial radio |
| Low voltage power | 30 to 50 | Suitable purchased supply and protected DC wiring |
| Enclosure and audio accessories | 20 to 40 | Simple enclosure, microphone or audio components and connectors |
| Initial test accessories and assembly consumables | 25 to 50 | Suitable dummy load and small build supplies; advanced instruments excluded |
| Delivery, replacement parts and iteration reserve | 55 to 100 | Allowance only; no delivery or import quotation obtained |
| **Station total** | **300 to 550** | Excludes the reusable workbench below |
| Basic workbench if nothing suitable is owned | 150 to 350 | Temperature controlled soldering equipment with power and stand, multimeter, hand tools and bench consumables |
| **Starting from zero with basic tools** | **450 to 900** | Assumes RF test equipment can be borrowed; this access is not yet confirmed |

The lower end is a target for a straightforward documented build. This range is not a ceiling for a new radio design. It does not include purchasing an oscilloscope, signal generator or spectrum measurement setup. If suitable shared equipment is unavailable, recost the measurement plan before committing to the transmitter.

The earlier EUR 300 to 500 figure described a basic kit based station. The EUR 300 to 550 figure here is a separate provisional component construction allowance with an explicit iteration reserve. Neither establishes that buying individual components will always be cheaper than a kit.

## Smaller first build

Target **EUR 120 to 200 in parts for the antenna and a working receiver**, excluding reusable tools. This is a provisional subset of the complete phase budget, not an additional station to buy. Include the oscillator, filtering, audio, power and connectors needed to turn a receiver circuit into a usable receiver. Check reuse against the selected final circuit before ordering; a separate experimental receiver may otherwise add cost.

If all basic tools must also be bought, this first milestone is approximately **EUR 270 to 550**, under the same assumptions. It demonstrates reception, not transmission or intercontinental two way communication. Spend in stages rather than ordering the entire station before the receive path works.

## Verified price anchors and optional kit comparison

Listed prices were checked on 2026-10-25. They are examples, not a compatible basket. USD figures are not converted into EUR and exclude unquoted delivery and import costs.

| Source | Observed listing | Meaning for this estimate |
| --- | --- | --- |
| [QRP Labs receiver and options](https://shop.qrp-labs.com/receiver) | USD 25 receiver with one band filter; USD 33 VFO option; USD 11 polyphase option | USD 58 for receiver plus VFO, or USD 69 with polyphase. Power, antenna and audio integration still required |
| [QRP Labs QMX](https://www.qrp-labs.com/qmx.html) | USD 102.47 kit; 3 to 5 W; SSB, CW and digital modes | Optional price benchmark. Surface mount parts are fitted; soldering and winding remain. Enclosure and other options cost extra |
| [PINE64 EU soldering equipment](https://pine64eu.com/product-category/devices/solderingirons/) | EUR 67.50 including VAT for the PINECIL V2 listing | Iron price only; check suitable power, stand and availability before ordering |
| [TME UNI-T UT33D+](https://www.tme.eu/it/details/ut33d%2B/multimetri-digitali-portatili/uni-t/) | EUR 13.06 gross for one on the directly opened listing | Basic multimeter price anchor; delivery additional |

The [receiver documentation](https://www.qrp-labs.com/receiver.html) specifies a local oscillator at four times the receive frequency and an I/Q output requiring a suitable stereo audio input. The polyphase option provides mono SSB audio. A laptop microphone socket is not automatically a suitable I/Q interface.

The QMX uses product specific encrypted firmware. It is a useful kit comparison, but does not offer unrestricted modification of every firmware block. Neither it nor the separate receiver module has been selected. Do not silently replace the owner's component construction objective with a preassembled transceiver.

## Practical feasibility

**Assessment: achievable as a progressive learning project.** Following a documented single band circuit is a realistic starting scope. Designing an original multiband SSB radio from a blank sheet requires substantially more RF knowledge, measurement and iteration, with no defensible fixed cost yet.

Three conditions matter:

1. **A feasible antenna installation.** A simple half wave dipole is approximately 10 m end to end on the 20 m band, or 20 m on the 40 m band, before practical adjustment. These are examples, not a selected band or installation. Height, placement, local noise and feed line routing also matter. See [ARRL dipoles](https://www.arrl.org/single-band-dipoles) and [limited space antennas](https://www.arrl.org/limited-space-and-indoor-antennas).
2. **Progressive soldering and fault finding.** Practice soldering, inspect connections, check supply rails and test each subsystem. A real circuit may need debugging even when built from a proven schematic. Our scheduling allowance is several weekends for a documented kit and weeks to months for a component build, depending on experience and faults. This is an estimate, not a completion promise.
3. **Access to measurement before transmission.** A multimeter is useful but cannot validate unwanted RF emissions. Arrange suitable shared laboratory or amateur association equipment for signal tracing, output power and spectral checks. Build and verify into a suitably rated load before antenna commissioning. Confirm applicable Italian operating prerequisites with [MIMIT](https://ispettorati.mise.gov.it/index.php/servizi/radioamatori/).

Low power HF voice contacts over long distances are possible, but antenna efficiency, interference and propagation strongly affect the outcome. The first phase succeeds when the station is reproducible and tested; the intercontinental contact has its own later milestone.

## Completion evidence and next decision

For the first receive milestone, retain the schematic, actual parts cost, antenna dimensions, construction photos and repeatable intelligible reception with frequency, mode and conditions recorded. For the complete first station, add the transmitter circuit, measured output and unwanted emission checks, switching and protection checks, and integrated controls.

Before a concrete order list, resolve only the inputs needed to select a compatible build: usable antenna space, tools and skills already available, and access to RF measurements. No owner budget, licence status, equipment inventory or installation has been assumed verified. No parts have been purchased and no hardware result is claimed.
