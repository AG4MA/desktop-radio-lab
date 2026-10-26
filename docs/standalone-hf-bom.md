# Standalone HF voice station: proposed bill of materials

Checked on 2026-10-26. This proposal follows the owner's requirement to assemble a radio that can receive and transmit voice without a computer during normal operation. Delivery country is Italy. The antenna site is tentatively a roof; its dimensions and cable route are not yet known. No purchase, construction or hardware test has occurred.

**The final delivered cost is not available.** The tables distinguish verified product prices from missing installation quantities, delivery charges and import costs. EUR prices are displayed VAT-inclusive prices except the OBI drill, whose current listing does not expose its VAT label. Prices in USD have no confirmed Italian import tax or handling included. Keep the currencies separate until a real payment quote exists.

## Build and capability

The proposed radio is the **QRP Labs QMX KIT, low-band version 80/60/40/30/20 m, built for 9 V**. The owner solders the through-hole components, winds the magnetic components, and assembles the controls and case. Surface mount components arrive fitted. The microphone, dummy load, antenna transformer and common mode choke are also kits to assemble. This is substantial kit construction, with published schematics, rather than an original circuit design or a radio built entirely from loose components. QMX application firmware is product-specific and encrypted.

The proposed antenna supports the first voice work on **40 m and 20 m** after installation and adjustment. QMX supports SSB voice at the manufacturer's nominal 3 to 5 W class; the 9 V transformer build is specified for approximately 4 to 5 W. Intercontinental contacts are a feasible objective under suitable propagation and antenna conditions, not a guaranteed distance or continuously available link. The other radio bands need an appropriate antenna and applicable operating privileges. This is the HF milestone in the [single project progression](workstreams.md); solar power and the later local emergency network remain subsequent work.

Normal SSB voice operation uses the microphone, headphones and front controls without a PC. **Initial firmware installation requires a computer and a USB data cable.** No separate programmer is needed. A computer may also help commissioning and later updates. References: [QMX features and firmware](https://www.qrp-labs.com/qmx.html), [operating manual 1_04_004](https://www.qrp-labs.com/images/qmx/manuals/operation_1_04_004.pdf).

## Radio, audio and operating power

Each quantity below is one unless specified. Stock is a reading of the public listing, not a reservation.

| Product and direct order page | Exact option or purchase unit | Displayed product price | Evidence and purpose |
| --- | --- | ---: | --- |
| [QRP Labs QMX](https://shop.qrp-labs.com/qmx) | KIT, 80/60/40/30/20 m | USD 102.47 | Listed for order; receiver, transmitter, display and controls in one kit. Do not select the assembled surcharge |
| [QMX enclosure option](https://shop.qrp-labs.com/qmx) | One enclosure | USD 20.00 | Cut and drilled metal case with panels, feet and screws |
| [QMX USB cable option](https://shop.qrp-labs.com/qmx) | USB A to C data cable | USD 4.65 | Initial firmware transfer. Confirm access to a computer with a USB A port, or reuse a suitable data cable |
| [QRP Labs dummy load](https://shop.qrp-labs.com/dummy) | One 50 ohm, 20 W kit | USD 8.50 | Listed stock: 179. Bench load with detector; connection cable/adapter is separate |
| [Reichelt KBK 102 2M](https://www.reichelt.com/it/it/shop/prodotto/cavo_di_collegamento_bnc_rg_58u_connettore_bnc_2_m-9205) | One 2 m RG58U, BNC male/male cable | EUR 1.95 | Available. Connects the radio to the dummy load without supporting its weight on the radio socket |
| [N8PIC QRP Microphone V2.2](https://radio.n8pic.com/n8pic-qrp-microphone-v2-2/) | KIT wired for QMX | USD 25.00 | Maker lists kit for sale; stock quantity not exposed. Includes PCB, capsule, PTT switch, stereo socket, foam and PETG backing |
| [LogiLink CA10100](https://www.tme.eu/it/details/ca10100/cavi-audio-video-rimanenti/logilink/) | One 1 m, 3.5 mm stereo TRS male/male cable | EUR 2.95 | Stock: 20. Connects microphone to radio |
| [Futura 8228-SUPERGLUE](https://futuranet.it/prodotto/colla-cianoacrilica-20-grammi/) | One 20 g bottle | EUR 3.80 | Available. The microphone maker recommends super glue to attach the supplied backing |
| [Mean Well GST25E09-P1J](https://www.tme.eu/it/details/gst25e09-p1j/alimentatori-a-spina/mean-well/) | One 9 V, 2.55 A adapter | EUR 15.61 | Stock: 51. EU plug and output cable included, 5.5/2.1 mm centre positive |
| [Philips SHP2500](https://www.euronics.it/tv-e-audio/cuffie-e-auricolari/cuffie/philips---shp2500-black-silver/112023161.html) | One pair | EUR 19.90 | Online order offered. 32 ohm, 3.5 mm stereo headphones; integral cable |

**This table's product subtotal is USD 160.62 plus EUR 44.21.** It excludes antenna, bench equipment and all delivery/import charges. N8PIC separately publishes **USD 15 international shipping**. This is not a complete station price.

### Verified interfaces

The microphone connects to the QMX Paddle socket: **tip = PTT, ring = microphone/bias, sleeve = ground**. PTT shorts tip to sleeve. Select the N8PIC QMX wiring, not its reversed Elecraft configuration. No second microphone capsule, PTT button or enclosure is required for the maker's proposed build. It has a PETG back rather than a fully enclosed front shell. Its linked assembly PDF returned 404; the product page and [maker's build video](https://youtu.be/ZtEwN7zzzgc) remain available.

Headphones use the separate audio socket. Their 32 ohm load and stereo connector match the operating manual; see the [Philips specification](https://www.documents.philips.com/assets/20231208/6ae9d3422e25422fb6f3b0d200ecba5e.pdf). A passive speaker cannot simply replace them.

Build the PA transformer for the selected 9 V supply, following the [transformer manual 1.00d](https://www.qrp-labs.com/images/qmx/manuals/transformer1_00d.pdf). The improved 9 V winding is WTST 3:3. Do not substitute a 12 V or 13.8 V supply into that build. The adapter's voltage, current, connector and polarity agree with the documented interface; actual voltage and received interference still require testing. Do not describe it as a measured low-noise radio supply.

The [dummy-load manual](https://www.qrp-labs.com/images/dummyload/dummyload.pdf) shows a female BNC, as on the radio. The listed BNC male/male cable completes the connection. Reichelt identifies RG58U; the same KBK 102 2M part is explicitly specified as 50 ohm in the [Junkers Profly catalog](https://www.junkers-profly.de/pdf_catalog/german/Katalog.pdf). The dummy load absorbs RF for tests and provides no communication range.

## Antenna and feed line, conditional on roof dimensions

The specific variant below contains 21 m of radiator wire and is nominally about 20 m long after adjustment. No available roof span, anchor strength, height or clearance has been established. This is a priced candidate, not a validated roof installation.

| Product and direct order page | Quantity | Displayed product price | Included or required function |
| --- | --- | ---: | --- |
| [HF Kits 10/(15)/20/40 EFHW](https://www.hfkits.com/product/10-15-20-40-endfed-antenna-kit/) | One Copper/Kevlar Wire variant, EF-10-15-20-40-KEV | EUR 46.00 | In stock. Wire, FT140-43, winding wire, capacitor, IP65 box, SO239 socket, mounting plate, end insulator, wire clamps, lug, heat shrink and kit hardware |
| [HF Kits common mode choke](https://www.hfkits.com/product/3-30-mhz-common-mode-choke/) | One CHOKE-BIFILAIR-43 kit | EUR 43.00 | In stock. FT240-43, winding wires, box, plate, two SO239 sockets and hardware |
| [RG-58C/U cable](https://www.hfkits.com/product/rg-58cu-coax-cable-per-meter/) | Metres to measure, in two cable sections | EUR 1.25 per metre | In stock. 50 ohm, 4.95 mm outer diameter |
| [PL259 solder plug, PL-CON-5MM](https://www.hfkits.com/product/pl259-connector-hyperflex5/) | Three plugs | EUR 3.25 each, EUR 9.75 for three | In stock. Seller explicitly includes RG58 compatibility |
| [BNC solder plug, BNC-CON-5MM](https://www.hfkits.com/product/bnc-connector-rg-58-hyperflex5-aircell5/) | One plug | EUR 5.50 | In stock. Seller explicitly includes RG58 compatibility |
| [HamRope 4 mm polyester](https://www.hfkits.com/product/hamrope_50_meter/) | One 50 m reel | EUR 15.50 | In stock. Purchase quantity is one reel; site sufficiency remains unverified |
| [HF Kits VULKTAPE](https://www.hfkits.com/product/vulcanizing-tape-protected-moisture/) | One 19 mm x 10 m roll | EUR 8.25 | In stock. Self-amalgamating tape for outdoor coax connectors; installation quantity remains to be checked |
| [HF Kits TIEWRAP01](https://www.hfkits.com/product/cable-ties-100-x-25-mm/) | One bag of 100, 100 x 2.5 mm ties | EUR 1.50 | In stock. Kit manuals use ties but do not specify dimensions; check fit on the mounting plates |

**The fixed antenna rows above total EUR 129.50, excluding coax and the unresolved installation items.** Do not turn this into a complete antenna quotation. No mast, roof brackets or counterpoise is assumed included. The tape and rope quantities are purchase units, not confirmed quantities for the whole installation.

Cable arrangement: **QMX BNC socket > BNC male to PL male cable > choke > PL male to PL male cable > EFHW transformer.** This uses exactly one BNC plug and three PL plugs. Their solder assembly does not require a coax crimper. Do not add the earlier 10 m BNC/BNC cable automatically as if it implements this arrangement.

Follow the [antenna transformer instructions](https://www.hfkits.com/build-instruction-impedance-transformer-for-end-fed-antennas/) and [choke instructions](https://www.hfkits.com/manual-common-mode-choke/). The antenna instructions warn that some photographs show one extra turn: use the schematic. Trim and check matching in the installed position. The manufacturer describes 10/20/40 m use without a tuner after adjustment; its 15 m operation requires a tuner. The proposed low-band QMX uses this antenna initially on 40 m and 20 m.

The manufacturer's [end-fed installation discussion](https://www.hfkits.com/end-fed-antennas-a-critical-view/) recommends common mode control and a counterpoise for home use. It gives 6.5 m and 3.8 m as example choke distances from this antenna's feedpoint. Those examples do not establish this roof's cable length. Counterpoise dimensions, return connection and choke placement must be designed and measured together. Do not assume a roof gutter is an approved return or protective earth connection.

A priced counterpoise material candidate is [HF Kits LITZEXP, insulated flexible 1 mm2 copper](https://www.hfkits.com/product/experimental-antenna-wire-1-mm2/) at **EUR 0.40 per metre**, in stock. Quantity and termination are not selected. The [RIPCA M3 lug](https://www.hfkits.com/product/cable-shoe-m3/) is EUR 0.20, but its accepted wire section is not specified on the listing, so it is not counted as a verified compatible termination.

## Bench equipment and consumables

Buy only items not already available. The following is a separately priced tool basket, not equipment incorporated into each replicated radio. A successful low-cost build may use borrowed tools, but no loan has been confirmed.

| Product and direct order page | Purchase unit | Displayed price | Purpose and availability |
| --- | --- | ---: | --- |
| [ATTEN ST-80](https://www.reichelt.com/it/it/shop/prodotto/stazione_di_saldatura_st-80_1_canale_80_w-290557) | One 80 W station | EUR 82.01 | Available; Italian 22% VAT shown. Iron, holder, sponge and mains cable included |
| [ATTEN T900-1.2D](https://www.tme.eu/it/details/t900-1.2d/punte-saldanti/atten/) | One 1.2 mm chisel tip | EUR 2.29 | Stock: 362. Separate from station; [ST-80 compatibility](https://www.reichelt.com/de/en/shop/product/soldering_tip_1_2_mm_chisel-shaped_straight-300268) documented |
| [UNI-T UT33D+](https://www.tme.eu/it/details/ut33d+/multimetri-digitali-portatili/uni-t/) | One multimeter | EUR 13.06 | Stock: 248. Leads and batteries included per [manufacturer](https://meters.uni-trend.com/product/ut33plus-series/) |
| [Piergiacomi TR-25](https://www.cedelettronica.com/it/prodotti/elettronica/tronchesino-taglio-raso-piergiacomi-tr-25/2894) | One flush cutter | EUR 9.03 | Available |
| [Futura VT046N](https://futuranet.it/prodotto/pinza-fine-a-becchi-lunghi/) | One long-nose plier | EUR 3.80 | Available |
| [Futura WT77837](https://futuranet.it/prodotto/set-7-cacciaviti-di-precisione-con-punte-magnetiche/) | One seven-piece screwdriver set | EUR 9.50 | Available; flat and Phillips sizes included, no hex keys |
| [Futura TS1515](https://futuranet.it/prodotto/trecciola-dissaldante-15-mm/) | One 1.5 mm x 1.5 m braid reel | EUR 3.50 | Available; for rework if needed |
| [Stanley 0-22-500](https://www.tme.eu/it/details/stl-0-22-500/lime-e-raschietti/stanley/0-22-500/) | One six-file set | EUR 5.50 | Stock: 26. Finish separated board edges |
| [Futura SOLD250GTX](https://futuranet.it/prodotto/stagno-per-saldatura-sn-pb-250-grammi-hight-quality/) | One 250 g reel, 1 mm SnPb, 60% tin | EUR 22.00 | Available, flux core. Specific flux chemistry is not stated |
| [Reichelt ISOBAND 19 SW](https://www.reichelt.com/it/it/shop/prodotto/cerniera_isolante_vde_25_m_larghezza_19_mm_nero-136323) | One 19 mm x 25 m roll | EUR 1.64 | Available. Electrical insulating tape required behind the QMX DC connector by assembly section 2.27 |

**This ten-item bench basket totals EUR 152.33 before delivery.** The microphone glue is already counted in the radio/audio table. Mechanical tool access and the optional bench supply below are additional. This is not a complete RF laboratory or a claim that all tools must be bought. The station has a Schuko mains plug; an appropriate available socket or replacement mains cable must be confirmed.

The [QMX assembly manual 1.04r](https://www.qrp-labs.com/images/qmx/manuals/assembly_1_04r.pdf) recommends a 60 to 80 W iron, a 1 to 2 mm chisel tip and 60/40 or 63/37 solder. This is why the earlier 25 W nominal SS204 and small lead-free reel are not carried forward as the QMX tool selection. The cheaper 100 g Futura leaded solder listings were out of stock when checked. The 250 g purchase unit is not an assertion of how much solder one radio consumes.

Access to suitable drilling, winding and general mechanical tools still needs confirmation. An adjustable current-limited supply is recommended for first power-up: the manual suggests about 7 V and a 250 mA limit if possible. The fixed 9 V operating adapter does not replace that diagnostic function. If buying rather than borrowing this bench equipment:

| Product and direct order page | Quantity | Displayed price | Verified function |
| --- | --- | ---: | --- |
| [Korad U202 at Reichelt](https://www.reichelt.com/it/it/shop/prodotto/alimentatore_da_laboratorio_0_-_30_v_0_-_5_a_150_w_stabilizz-395113) | One | EUR 66.63 | Available. Adjustable 0 to 30 V, 0 to 5 A, CV/CC; mains cable included, output leads separate |
| [Futura CAVIBCRN](https://futuranet.it/prodotto/cavo-con-spinotti-a-banana-e-coccodrilli/) | One red/black pair | EUR 2.50 | Available. 4 mm banana to crocodile clips |
| [QRP Labs DC cable option](https://shop.qrp-labs.com/qmx) | One 2.1 mm plug with 20 cm wire | USD 1.00 | Connects the clip leads to the radio; verify centre-positive polarity with the meter before use |

**Optional bench-power purchase subtotal: EUR 69.13 plus USD 1.00**, before delivery. This is separate from the ordinary 9 V operating adapter. These are nominal electrical capabilities, not a measured commissioning result.

### Mechanical tool access

The HF Kits enclosures need drilling. Their instructions specify 3.5, 5, 6 and 16 mm holes. The optional QMX case is already machined. These reusable tools are additional only where equivalent tools cannot be reused or borrowed. One unit or set per row is priced; no existing ownership is assumed.

| Product and direct order page | Displayed price | Function and availability |
| --- | ---: | --- |
| [Einhell TC-ID 650 E, OBI 5624127](https://www.obi-italia.it/p/5624127/trapano-a-percussione-einhell-tc-id-650-w) | EUR 28.79; VAT label not exposed on current listing | Few units available. Electronic speed control, 1.5 to 13 mm chuck. Use rotary mode for the boxes and the prescribed wire-twisting fixture for the PA transformer |
| [Metabo 627153000, 19 HSS-G bits](https://www.tme.eu/it/details/mtb.627153/set-di-punte/metabo/627153000/) | EUR 20.36 gross | Stock: 11. Includes 3.5, 5 and 6 mm |
| [C.K T3010 1, 4 to 20 mm step drill](https://www.reichelt.com/it/it/shop/prodotto/punta_a_gradini_hss_4_-_20_mm-334280) | EUR 20.45 gross | Available. Includes 16 mm. Exact shank diameter remains to be confirmed before treating the drill pairing as fully verified |
| [Stanley 0-10-150 knife](https://www.tme.eu/it/details/stl-0-10-150/coltelli-forbici/stanley/0-10-150/) | EUR 2.14 gross | Stock: 159. Retractable blade for wire preparation |
| [Stanley 0-30-497, 5 m tape measure](https://www.tme.eu/it/details/stl-0-30-497/attrezzi-di-misura/stanley/0-30-497/) | EUR 4.54 gross | Stock: 111. Measure wire in successive lengths and mark hole positions |
| [Edding 3000 black marker](https://www.reichelt.com/it/it/shop/prodotto/permanent_marker_1_50_-_3_00_mm_schwarz-118166) | EUR 2.26 gross | Available. Mark enclosure holes |
| [Proxxon 23080 tool set](https://www.tme.eu/it/details/prn23080/kit-di-chiavi/proxxon/23080/) | EUR 44.23 gross | Stock: 13. Includes sockets 5.5, 8 and 10 mm for standard M3/M5/M6 nuts, handle, extension and ratchet |
| [Futura 8240-TP509 hot-air gun](https://futuranet.it/prodotto/pistola-ad-aria-calda-1500w-con-temperatura-regolabile/) | EUR 35.00 gross | Available. Adjustable 50 to 500 degrees C with reducer nozzle, for the supplied heat-shrink sleeve. Schuko plug |

The seven explicitly gross-priced products excluding the drill sum to **EUR 128.98**. The drill is separately listed at EUR 28.79. Neither figure includes delivery or establishes a complete working tool setup. Reusing equivalent tools avoids those purchases; this is not a minimum entry cost.

The [Einhell specification](https://www.einhell.de/p/4258682) verifies speed control and chuck range. The [C.K product sheet](https://www.farnell.com/datasheets/1905504.pdf) verifies the cutting steps but omits numerical shank diameter. The [Proxxon sheet](https://www.proxxon.com/en/pdf/23080.pdf) identifies the socket sizes. The QMX manual does not specify the knob grub-screw drive/size or confirm a supplied key, so no particular Allen key is claimed to fit. Resolve these fit details with the supplied parts or vendor before buying replacements.

## Commissioning and outstanding costs

The QMX includes internal power/SWR indication, protection and microphone tests. Its power/SWR readings are not precision measurements. Its SSB calibration can run from the LCD with a 50 ohm load. These functions do not independently establish spectral purity after assembly. Access to an appropriate RF test setup and experienced assistance has not been confirmed or costed.

Before completing the shopping cost, resolve:

1. Roof span and attachment points, usable height/clearances, both coax sections and cable entry route. The roof was proposed, not surveyed.
2. Counterpoise material and connection, outdoor connector sealing, cable support and strain relief, and any roof mounting, mast or installation protection required by the actual site. Quote professional roof work if needed.
3. Existing tools and access to drilling, current-limited power and RF measurements. Confirm step-drill shank fit, QMX knob fastener tool, available mains sockets and mounting-plate tie fit. Borrowing is an option, not a verified zero-cost arrangement.
4. Retailer delivery to the actual destination, destination VAT treatment, import taxes/handling and currency conversion charges. Stock and variant prices must be reconfirmed when ordering.
5. Operator qualification and station authorization status, with any applicable fees separate from the hardware. Follow the [MIMIT amateur radio procedures](https://ispettorati.mise.gov.it/index.php/servizi/radioamatori/) before transmission.

Published shipping information, not a combined destination-specific checkout quote:

| Seller | Verified public information | What remains open |
| --- | --- | --- |
| [QRP Labs](https://qrp-labs.com/shipping.html) | Most relevant international orders ship from Turkey; courier options depend on destination | Configured order shipping, import tax and handling |
| [N8PIC](https://radio.n8pic.com/n8pic-qrp-microphone-v2-2/) | USD 15 international shipping | Stock fulfilment and Italian import charges |
| [HF Kits](https://www.hfkits.com/shipping/) | Delivery calculated in cart/checkout | Actual antenna quantities and destination quote |
| [TME](https://www.tme.eu/it/how-to-buy/7385/Modalita-e-spese-di-trasporto/) | EUR 7.20 gross standard ground delivery up to 15 kg; remote-area surcharges may apply | Final basket and destination applicability |
| [Futura](https://futuranet.it/condizioni-di-vendita/) | EUR 5.90 for prepaid online orders from EUR 25 to 149.99 | Final order contents and checkout confirmation |
| [Euronics headphone listing](https://www.euronics.it/tv-e-audio/cuffie-e-auricolari/cuffie/philips---shp2500-black-silver/112023161.html) | EUR 4.90 delivery displayed | Destination and fulfilment confirmation |
| [OBI drill listing](https://www.obi-italia.it/p/5624127/trapano-a-percussione-einhell-tc-id-650-w) | EUR 3.99 delivery displayed | Destination and final tax presentation |
| Reichelt and C&D | Product prices checked above | Delivery not quoted |

No delivered total, exchange-rate estimate, spare-part contingency or installer allowance has been invented. The previous [price comparison](product-price-check.md) remains historical context; do not add its receiver, alternative supply or tools to this proposal.
