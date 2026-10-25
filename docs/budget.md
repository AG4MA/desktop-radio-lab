# Planning costs

**Scope correction:** the owner prioritizes DIY construction and clarified two distinct projects: the homemade HF station and the autonomous emergency network. The figures below mainly describe complete new commercial equipment configurations, not minimum entry costs. See the [revised DIY path](workstreams.md), including a provisional EUR 300 to 500 starting budget for a low power kit based HF station. The commercial network budget is not a validated DIY minimum. EME is parked.

Checked on 2026-10-25. These are estimated whole system budgets derived from current component listings, not configured quotations or purchases. Assume new equipment and an existing computer. Allow for Italian checkout VAT adjustments and shipping before ordering; promotional prices and stock can change.

The station budgets include ordinary power, an appropriate basic antenna, cable and simple mounting. They exclude professional roof work, towers, site rent, administrative fees and the common workbench. Different goals reuse some equipment, so these totals should not be added together.

## Existing objectives

| Objective | Estimated total EUR | Configuration assumption |
| --- | --- | --- |
| EME lunar reflection | 5,000 to 10,000 or more | An initial digital EME station with an all mode radio, directional antenna system, pointing, suitable RF chain and power; target contacts with well equipped stations, not guaranteed voice or reception of its own echo |
| QO-100 satellite voice | 1,800 to 3,000 | Complete local transmit and receive chain, including conversion, suitable IF radio or SDR, dish, feed, power and cable |
| Low orbit satellite FM | 350 to 800 | Manual directional antenna and radios that allow listening to the downlink during transmission; no automatic tracking and no SSB satellite capability assumed |
| Intercontinental HF voice | 1,500 to 2,300 | A 100 W class HF transceiver, power supply and a simple suitable wire antenna installation |
| Local VHF/UHF desk station | 550 to 900 | Dual band FM mobile radio used at the desk, power supply, external antenna and feed line |
| Local SDR reception | 180 to 350 | Receiver, simple or original antenna, cable and adapters; existing computer |

Reserve another EUR 150 to 350 once for basic soldering tools, a multimeter, hand tools and small parts if none are owned. This is an unquoted planning allowance. Specialist RF instruments and substantial mechanical work can increase the advanced budgets.

## Observed component price anchors

These individual listings anchor the estimates. They are not a compatible shopping basket. VAT is included only where the source explicitly states it; the delivery country may change the final tax amount.

| Component and source | Displayed price | Qualification |
| --- | --- | --- |
| [SDRplay RSP1B](https://shop.funk24.net/SDRplay-RSP1B-SDR-Empfaenger-1-kHz-bis-2-GHz) | EUR 155 | VAT included according to listing; receiver and USB cable |
| [Yaesu FTM-150E ASP](https://www.wimo.com/en/yaesu-ftm-150easp-vhf-transceiver) | About EUR 330 | VAT included; radio only, no cashback deducted |
| [Yaesu FT-710](https://www.wimo.com/en/yaesu-ft-710-shortwave-transceiver) | From EUR 1,125 | VAT included; exact version and external power supply still to select |
| [Alinco DM-30E](https://www.avera.eu/brands/alinco-products.html) | EUR 148 | VAT included; 20 A continuous, 30 A maximum, actual radio load must be checked |
| [Yaesu FT-4XE](https://www.wimo.com/de/ft-4xe) | About EUR 80 each | VAT included; amateur handheld, not a licence free PMR446 radio |
| [DXPatrol QO-100 full duplex V2](https://dxpatrol.pt/produto/dxpatrol-full-duplex-qo-100-groundstation/) | EUR 950 | Tax treatment needs checkout confirmation; transverter with LNB and GPS antenna, not a complete station |
| [Icom IC-9700](https://www.wimo.com/it/ic-9700) | EUR 1,979 | VAT included; external power supply additional |
| [Yaesu G5500DC](https://www.avera.eu/yaesu-g5500dc.html) | EUR 1,058 | VAT included; rotator and controller, cable additional |
| [13 element 144 MHz EME Yagi](https://hamshop.nl/product/13-elements-144mhz-super-yagi-eme-antenna/) | EUR 457 | An 8 metre boom and order lead time; mechanical compatibility not selected or verified |
| [Midland G9 Pro](https://www.midlandeurope.com/index.php/it_IT/prodotti/g9-pro) | EUR 109 each | Italian VAT included; compliant PMR446 version required, stock to recheck |
| [Midland Alan 42 DS Lithium](https://www.midlandeurope.com/it_IT/prodotti/alan-42-ds-lithium-cb-midland) | EUR 199 each | Italian VAT included; portable CB with battery and USB charging |
| [Midland M-Mini](https://www.midlandeurope.com/it_IT/prodotti/midland-m-mini?variantCode=C1262) | EUR 86 | Italian VAT included; CB radio, antenna and station power additional |
| [Yaesu DR-2XE at FLQ](https://www.flqelettronica.it/description.asp?item=1857) | EUR 1,399 | Taxes included; repeater equipment only |
| [Yaesu DR-2XE at WiMo](https://www.wimo.com/it/radiotrasmettitore/dr-2xe) | EUR 899 | Promotional VAT inclusive listing; direct page showed availability from 2027-01-15, so not treated as immediate stock |
| [Victron SmartSolar 75/15](https://www.monzacamper.it/shop/prodotto/victron-smart-solar-mppt-75-15a/) | EUR 82.90 | Italian VAT included; small charger example, not automatically suitable for the larger repeater array |
| [LiTime 12 V 50 Ah family](https://www.mybait.de/litime-lifepo4-batterie) | EUR 149.99 for 50 Ah | VAT included in listing; delivery tax, low temperature protection and exact version need checking |
| [Renogy 100 W lightweight panel](https://eu.renogy.com/products/100w-lightweight-monocrystalline-solar-panel) | EUR 116.99 | Tax included; backordered listing, used as a cost anchor only |

## Solar communication network

The owner asked to include a base left in place on solar power and portable radios for other people. City or flat countryside are the assumed terrain scenarios. Four portable radios are a costing assumption, not a confirmed group size. No maximum distance has been set and no coverage has been measured.

| Architecture | Estimated total EUR | What is included and what it achieves |
| --- | --- | --- |
| Four PMR446 radios with solar charging | 800 to 1,300 | Four compliant portable radios, spare energy and a shared solar charging point; direct radio links only |
| Staffed CB base plus four portable CB radios | 1,500 to 2,300 | One base radio, external antenna and feed line, four portables and a solar power system; a person operates the base, with no automatic relay |
| Automatic amateur repeater plus four amateur handhelds | 3,500 to 7,000 | Repeater, filtering or appropriately isolated antenna system, feed line and mounting, solar and battery system, protected enclosure, handhelds and commissioning allowance; site and operator authorization required |

For the PMR446 option, allocate roughly EUR 320 to 440 for radios, EUR 400 to 650 for the solar charging equipment and EUR 80 to 210 for spare batteries, charging accessories and margin. This is a shared charging point: it does not recharge radios remotely or increase radio coverage.

For the automatic repeater, use the following engineering allowances before site design:

| Subsystem | EUR allowance |
| --- | --- |
| Repeater | 900 to 1,600 |
| Duplexer or equivalent RF isolation | 350 to 700 |
| Antenna, feed line and simple mounting | 250 to 600 |
| Solar array, battery, suitable MPPT and power conversion | 700 to 1,600 |
| Enclosure, DC protection and weather provisions | 150 to 400 |
| Four handhelds and charging provisions | 320 to 600 |
| Tuning, commissioning and contingency | 830 to 1,500 |
| Total planning envelope | 3,500 to 7,000 |

The solar sizes are not finalized. A repeater often consumes energy continuously while waiting, as well as while transmitting. Example only: an average load of 20 W consumes 480 Wh per day. A 12.8 V, 100 Ah battery with an assumed 80 percent usable net energy provides about 51 hours without solar input. Three days at that load require 1,440 Wh net, or at least 1,800 Wh nominal under the same assumption, before additional design margin.

A hypothetical 400 W array with two equivalent full sun hours and 70 percent net yield produces 560 Wh per day. This is an illustration, not a winter production forecast. Location, shading, cloudy days, battery temperature and the handheld charging load must be included before promising autonomy. Use appropriate battery charging temperature protection for an outdoor installation.

## Service and installation constraints

PMR446 and CB equipment meeting the applicable requirements can be used in Italy without an amateur licence. PMR446 is limited to compliant handheld equipment with integral antennas and a maximum 500 mW ERP; it cannot be used as a repeater or fixed infrastructure. See [MIMIT](https://ispettorati.mise.gov.it/index.php/servizi/dispositivi-debole-potenza) and [CEPT ECC Report 369, section 3](https://docdb.cept.org/download/4878).

Amateur operation requires the relevant operator credentials, callsign and general authorization. Giving a handheld to an unqualified friend does not extend the owner's authorization to that person. A repeater at a remote site requires the applicable separate authorization and callsign; a repeater at the holder's residence or domicile has a notification route under article 143. Check the exact site with the competent inspectorate. The MIMIT lists a EUR 20 annual contribution for applicable repeater authorizations; administrative costs are excluded above. See [MIMIT radioamateur services](https://ispettorati.mise.gov.it/index.php/servizi/radioamatori/) and [articles 134 to 145](https://www.mimit.gov.it/images/stories/documenti/allegati/artt_da_134_a_145_del_CdC.pdf).

A professional private radio network on assigned frequencies is a separate route requiring an eligible applicant, a technical design and an individual quotation. Eligibility for this proposed family or friends group has not been established. See [MIMIT private radio networks](https://www.mimit.gov.it/index.php/it/comunicazioni/radio/autorizzazioni-e-licenze/radio-ad-uso-impresa).

## Proposed first test

Use two appropriate portable radios at the intended locations before buying a full group kit. An example pair of G9 Pro radios at the manufacturer's listed price costs EUR 218 and can remain in a larger direct PMR446 kit. Select the permitted service before ordering. A PMR446 coverage test is not a validation of a future amateur repeater installation.

Record intelligibility at the required locations in the city or countryside. For a later solar prototype, disconnect external power and measure energy use and charging. A 72 hour autonomy test is a proposed engineering target, not a verified capability. Internet independence, coverage, unattended operation and voice privacy are separate properties; this project claims no protection against deliberate interference or conflict damage.
