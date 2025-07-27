# USB-Charger-5V-Batteries
A USB Charger for 5V Li-Ion batteries. It is designed to charge from a usb port, or something that will give 5V, 0.5A.

The circuit has a few protection circuits:
- A current limiter circuit so that the battery charges safely.
- A reverse polarity protection in case the battery is plugged in backwards that will not allow the circuit to start.
- A circuit that will stop the charging once it's done.

The PIC18 is used to monitor the charging and stop it when it's done and to light the 2 LEDs, one for when the charging is in process and the other for when it's done.\
The PIC18 is utilised more for convenience as the entire circuit could have been fully analog.

The schematics can be found in the [Charger USB.pdf](https://github.com/Str4ton/USB-Charger-5V-Batteries-/blob/main/Charger%20USB.pdf) file.
