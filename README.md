# M207_Geeetech_A20M
Marlin 2.0.7 for Geeetech A20M Printer

This is an implementation of the Marlin software for a modified Geeetech A20M 3D-printer. It has previously received the TMC2208 motor drivers and a BLTouch module. In the implementation the UBL-Leveling is activated and the Z-zero position is determined via the BLTouch module.
With the configuration files, together with a fresh Marlin Project Rel. 2.0.7 installation it is also easily possible to adapt the software.

Then the PID constants should be determined with M303 and added to the software, but this is also possible over Code-Commands.

With BLTouch-module the table screws can be completely loosened (uppermost position). 

Attention: Without BLTouch this leads to a collision of the nozzle with the table if the Z-position is to be zeroed via the XMin limit switch.

The work is motivated by the preliminary work of MucMoe in https://www.thingiverse.com/thing:3882087
