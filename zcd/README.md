
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

## Components
 - R1,2 220k 1/8W
 - R3 47k 1/8W
 - R4 1k 1/8W
 - R6 10k 1/8W
 - D1,2,3,4,5 1N4148
 - C1 1n 16v
 - C2 10μ 16v
 - U1 4N28 (4N35)

## References
 - [Zero Crossing Detectors and Comparators](https://sound-au.com/appnotes/an005.htm)
 - [DIY - Isolated High Quality Mains Voltage Zero Crossing Detector (DEXTREL)](https://dextrel.net/design-ideas-2/mains-zero-crossing-detector.html)
