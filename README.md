# PIC12F675MPPT
Solar MPPT circuit.

This is simple MPPT for solar panel.
Firmware v1~v5 is tested. Last firmware v5 working good in my usage.

11 mili-ohm N-ch logic level FET(BUK9511) used for current sensor. 
It can replace by 11 mili-ohm or higher Rds-on resistance logic level FET.

Transistor 2N2222A -> BC547 or compatible
Transistor 2N2907A -> BC557 or compatible

L1 100~330uH

LM358N can replace by other pin-compatible regular OP-AMP.

D8-D9 used for 3.6v Reference. Each has about 1.8v voltage drop.

Q1 gate voltage is 3.6v. It's depend on FET specification.

Q1, Q2 can skip heat spreader with low POWER Solar panel. No heat with 10W panel.
