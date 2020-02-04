# Fuel-meter
Basic live readout of fuel being consumed directly from injectors on 2006 DL1000

Takeing the injector pulses and calculate duration to create a read out of ML/sec of fuel used.
This will simply take the switched ground injector lead and run it through a level shifter circuit and into a digtal GPIO pin on the Khadas VIM3 SBC.
