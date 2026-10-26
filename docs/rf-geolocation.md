# Scientific RF geolocation experiment

**Requested:** 2026-10-26. **Status:** objective documented; design and experiments have not started.

## Goal and scope

Build and understand a system that estimates a transmitting antenna's location from received radio waves. Start with reference transmitters or participating stations whose locations can be checked independently. This is an additional scientific objective within Desktop Radio Lab, alongside the progression from homemade construction to intercontinental HF contacts and autonomous emergency stations.

The estimator may use RF observations, known receiver positions, antenna calibration and timing references. It must not obtain the transmitter's position from transmitted GPS/APRS coordinates, IP geolocation or callsign databases. Keep its actual position separate as ground truth for validation. Locating an antenna does not by itself identify an operator or prove their location.

The transmitter must emit a receivable signal during observations. Ordinary reception of speech alone does not automatically provide coordinates.

## Proposed progression

1. **Direction finding:** build or assemble a suitable directional receiving setup and measure bearings to a reference transmitter. Record calibration, repeatability and directional ambiguities. One bearing generally establishes a direction, not a distance.
2. **Position estimation:** combine bearings from separated, known observation positions. Sequential observations require a stationary reference transmitter and comparable conditions. Evaluate receiver geometry, reflections and measurement error rather than assuming an exact intersection.
3. **Time difference of arrival (TDOA):** assess simultaneous observations from synchronized receivers at separate sites and their signal processing requirements. Relative arrival times constrain the source location. Receiver count, placement, timing accuracy, receiver delay calibration and signal suitability must be established before implementation.
4. **HF extension:** investigate long distance skywave localization separately. Ionospheric propagation and multiple paths complicate the relationship between measured direction or delay and transmitter position. Local results must not be presented as proof of intercontinental geolocation performance.

Direction finding and TDOA are documented in the [primary technical references](sources.md#rf-geolocation-references). They are candidate methods, not capabilities already demonstrated by this project.

## Evidence required

For each trial, record the method, time, frequency and mode, receiver positions, antenna configuration, calibration, synchronization where applicable, raw observations and processing version. Then retain:

| Result | Required record |
| --- | --- |
| Position estimate | Coordinates and an uncertainty region, with the method used to derive it |
| Validation | Independently recorded reference position and horizontal position error in metres |
| Repeatability | Results from repeated trials, including failed, ambiguous and rejected estimates |
| Limitations | Geometry, signal quality, reflections, timing and propagation assumptions |
| Reproducibility | Build details, procedure and shareable measurement data with an explanation of any redactions |

The first demonstration is complete when a documented setup produces a position estimate from radio observations, and repeated trials quantify its error against separately held ground truth. This demonstrates the method under the recorded conditions. It does not establish an accuracy guarantee. No numerical accuracy or range target is selected before a feasibility experiment.

## Equipment and integration

The [standalone HF bill of materials](standalone-hf-bom.md) is not a complete geolocation system. The QMX proposal alone has not been validated for direction finding or synchronized observations across multiple sites.

Antennas, receivers, calibration equipment, timing, processing and their verified costs remain to be selected. Preserve the requirement for normal HF voice use without a PC. Whether this separate experiment uses embedded processing, an external computer or later offline analysis remains open; no PC requirement is added to normal radio operation.

Use reference signals and transmissions permitted for the selected service. This experiment does not authorize private or protected communication interception. Keep precise home locations and participant details out of public datasets; publish measurements from suitable test sites or a clearly documented privacy-preserving dataset.

**Next design step:** select a local reference experiment and its band, then verify a reproducible direction-finding setup and its complete parts list. No hardware purchase is authorized by this plan.
