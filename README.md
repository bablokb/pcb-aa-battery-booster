Project pcb-aa-battery-booster
==============================

This is a small PCB with a boost-converter to provide stable 3V3 from two (AA) batteries.
The same design could be used for an output of 5V, using a different boost-converter.


Motivation
----------

When powering a Pico from batteries, you need a stable voltage. In contrast to what
the datasheet says, a Pico-W won't boot with VSYS below about 2.55V.

Two batteries in series provide a nominal voltage of 3V, but this is only true
for fresh batteries. See <https://en.wikipedia.org/wiki/Alkaline_battery> for
a table with voltages for a given capacity level. According to this table,
the voltage will drop to a critical level already at about 80% of the batteries
nominal capacity (depending on load).


Hardware
--------

License
-------

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International
License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]:
https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
