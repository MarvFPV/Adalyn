# Adalyn

36key QAZ-like handwired keyboard based on the great idea by somepin here on GitHub, check out his repo [here](https://github.com/somepin/qal-handwire)


Currently, the top and bottom are pretty much a friction fit, be aware of that when printing / ordering this case from a fab.

## Required components for handwires

* 36 MX style switches
* 2 2u MX platemount stabs
* 36 Diodes
* a Promicro
* one of ai03's [unified daughterboards](https://github.com/ai03-2725/Unified-Daughterboard)
* a few cables to wire up the matrix
* 4 m3x6mm screws
* 4 m3x8mm countersunk screws 

I personally tend to remove the microUSB connector from the Promicro and solder it directly to a unified daughterboard, that's also why the Promicro cutout may not fit with the USB connector still on the PCB. (I should really write up some documentation on that ^^)

## Required components for the pcb:

- newest pcb based on Atmega32u2

- all necessary components can be found in the bom for jlc/lcsc [here](/PCB/production/smt-assembly) 



## State of PCB:

[Files are ready, prototype not ordered yet]  

- Design moved to an Atmega32u2 as Mcu 

- silkscreen and re-routed, positioned design by [ScatteredDrifter](https://github.com/ScatteredDrifter/Adalyn)



## Render of PCB:

![frontside](/images/pcb-front.png)

![backside](/images/pcb-back.png)
