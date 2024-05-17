# Manufacturing notes R0C

This board is all THT components, and as such is easy to hand solder.

## BOM

| Reference | Component (Link to Digikey) | Notes |
| --------- | ------------------------ | ----- |
| D1-D4     | [1N4001](https://www.digikey.se/en/products/detail/diotec-semiconductor/1N4001/13164614)                          | Populate if the corresponding relay (K1-K4) is populated |
| F1        | [Schurter FRT 250F 500 mA](https://www.digikey.se/en/products/detail/schurter-inc/7100-1062-13/639858)            | Populate if U1 is populated |
| K1        | [TE RT314012](https://www.digikey.se/en/products/detail/te-connectivity-potter-brumfield-relays/RT314012/1128622) | Populate if needed |
| K2-4      | [Panasonic ALDP112](https://www.digikey.se/en/products/detail/panasonic-electric-works/ALDP112/13617701)          | Populate if needed |
| J1-J6     | [TE 160650-2](https://www.digikey.se/en/products/detail/te-connectivity-amp-connectors/160650-2/2054174)          | Populate J2 if U1 is populated, populate J3-J6 if the corresponding relay is populated. Possible to replace with TE 62409-1 if a flat mounting is desired |
| U1        | [XP Power ECE10US12](https://www.digikey.se/en/products/detail/xp-power/ECE10US12/4487498)                        | Only needed if not supplying power to APEC via CN3 |