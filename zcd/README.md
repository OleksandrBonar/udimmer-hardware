
# Zero Cross Detector

![ZCD](scheme_v2.png?format=raw)

## Features
 - Highly accurate mains zero crossing detection
 - Fully isolated and low voltage safe output
 - Ultra-low power consumption; worst case power dissipation < 120mW
 - Produces symmetrical pulses around zero crossings
 - Output pulse stays constant, independent of the mains voltage
 - Very low parts count, no precision components required
 - All components can be low voltage SMD
 - Works over all voltage ranges (100VAC/240VAC), without modification
 - 50Hz/60Hz compatible
 - 50Hz produces a 0.5ms ZC pulse, 60Hz produces 0.44ms ZC pulse
 - Highly stable with varying temperature and aging

## Bill of Materials
| # | Designator | Quantity | Value | Part Number | Manufacturer | Package Type | Description |
|---|---|---|---|---|---|---|---|
| 1 | R1, R2 | 2 | 220k |   |   |   | 1/8W |
| 2 | R3 | 1 | 47k |   |   |   | 1/8W |
| 3 | R4 | 1 | 1k |   |   |   | 1/8W |
| 4 | R6 | 1 | 10k |   |   |   | 1/8W |
| 5 | D1, D2, D3, D4, D5 | 5 |   |   | ST | DO-35 | 1N4148 100V 0.15A 8ns |
| 6 | C1 | 1 | 1n |   |   |   | 16V |
| 7 | C2 | 1 | 10μ |   |   |   | 16V |
| 8 | U1 | 1 |   |   | Vishay Semiconductors | DIP-6 | 4N28 (4N35) CTR > 10 % |
| 9 | Q1 | 1 |   |   |   | TO-92 | 2N3904 NPN 60V 0.2A |

## References
 - [Zero Crossing Detectors and Comparators](https://sound-au.com/appnotes/an005.htm)
 - [DIY - Isolated High Quality Mains Voltage Zero Crossing Detector (DEXTREL)](https://dextrel.net/design-ideas-2/mains-zero-crossing-detector.html)
