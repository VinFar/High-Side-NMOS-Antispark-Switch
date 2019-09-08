High Side milliOhm NMOS Anti Spark Switch
===
# Introduction

<img src=front.PNG width="auto">
<img src=back.PNG width="auto">
<img src=PCB.PNG width="auto">



This PCB is an Anti-Spark switch for high capacitive loads (150A, 60V) and was especially designed for electric longboards.
It uses two IRFS7530 milliOhm N-MOSFET (can be easily upgraded to more FETs), which have a Rdson of 0.7 mOhm in the worst case,
which enables a maximum current of around 450A with sufficient cooling.

Inspired by the [DieBieMS](https://github.com/DieBieEngineering/DieBieMS) it uses a BQ76200PWR HighSide MOSFET driver,
to enable the high switching with NMOS.

## Features

The PCB includes the following features:
  - dimensions: 74mm x 38.2mm
  - maximum current of at least 150A (more with more copper and cooling)
  - maximum voltage of 60V
  - 12V 50mA output
  - controlled dI/dt with capacitor and current limiting resistor
  - two IRFS7530 N-channel MOSFET
  - BQ76200PWR High Side MOSFET Driver
  - A TPS7A4101DGNR 12V 50mA LDO
  - A holder for a LittleFuse BF1
  - 4 pin JST XH connector for external switch or MCU
  - exposed pcb traces to add solder or a copper bar for lower resistance

### Versions
  - V0.1 is the initial version (08.09.19)
