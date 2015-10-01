Base Convert
============

Some basic conversion scripts written for myself as busy-work.

### CV ###

Convert value from DEC, HEX, or BIN to another base using bc command.

	Usage: cv [BASE IN] [BASE OUT] INPUT_TEXT or FILENAME

Valid base inputs are:
* DEC
* BIN
* HEX

Input files must be a line seperated list of values.


### ROT ###

Does ROT 13 and ROT 47 encoding/decoding using tr.
Honestly I have no idea how the REGEX works.

	Usage: rot [ 13 || 47 ] {QUOTED TEXT}

