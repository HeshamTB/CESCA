This EEPROM is a translation layer between the Funct / control signals and the inputs of the 74hc181. It also controls the shift buffers and the Carry flag (this way the active low signal from the 74hc181 is inverted only when the operation is ADD, since the borrow from SUB doesn't need to be inverted).

There is no C++ code for generating this file because it's much simpler than the other EEPROMs, so this one was made manually.