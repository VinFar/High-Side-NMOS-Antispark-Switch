High Side milliOhm NMOS Anti Spark Switch
===
# Introduction

This PCB is an Anti-Spark switch for high capacitive loads (200A, 60V) and was especially designed for electric longboards.
It uses 10 TPW1R306PL milliOhm N-MOSFET, which have a Rdson of around 90 uOhm in the worst case,
which theoretically enables a maximum current of around 250A with sufficient cooling.

Inspired by the [DieBieMS](https://github.com/DieBieEngineering/DieBieMS) it uses a BQ76200PWR HighSide MOSFET driver,
to enable the high switching with NMOS.

<img src=front_with_copperbar.PNG width="auto">
<img src=with_heatsink.PNG width="auto">
<img src=PCB.PNG width="auto">


## Features

The PCB includes the following features:
  - dimensions: 74mm x 38.2mm
  - maximum current of at least 125A (more with additional copper and cooling)
  - maximum voltage of 60V
  - controlled dI/dt with capacitor and current limiting resistor
  - 10 TPW1R306PL N-channel MOSFET
  - BQ76200PWR High Side MOSFET Driver
  - A TPS7A4101DGNR 12V 50mA LDO
  - A holder for a LittleFuse BF1
  - 4 pin JST XH connector for external switch or MCU
  - exposed pcb traces to add solder or a copper bar for lower resistance

### Versions
  - V0.1 is the initial version (08.09.19)
  - V0.2 uses 10 TPW1R306PL mosfet instead of two IRFS7530 (09.09.19)
