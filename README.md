# RealTimeLibs328
Here you can find some modiefied libs for the Atmega328:
all routions are interrupt base and are designed to work on a high resopsive environment, 
that means blocking an interrupt for more than ~50us might have an negative impact on the function.
- wireLight simplefied interface, none blocking, master only, less RAM usage, faster
- SWUsart works upto 27800Baud on a 16Mhz Board, uses the inputcapture and outputcompare register, i.e fine for GPS
- eeprom, none blocking

