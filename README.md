


## TEC Element
Peltier element
CPU cooler 
fans

## TEC Controller

[Schematic]() | [BOM]() | [Layout]() | [Code]()

The "TEC Controller" is a sub-assmebly responsible for performing low level control operations
of the "TEC Element" in response to commands from the "Master Controller". Specifically, it
manages the following:
   - selecting a voltage level for the TEC
   - enabling/disabling the TEC
   - controlling FAN speed via a PWM signal
   - controlling TEC activation timing
   - controlling fan activation timing relative to TEC activation

The following diagram shows a high level view of the "TEC Controller":

![TEC block diagram][TEC Block Diagram]



#### Wiring Harnesses

   - [Power](https://google.com)
   - [Control]()
   - [Prog]()
   - [Element]()


#### Commands

 | Name            | Command Format | Response Format | Code Link |
 | --------------- | -------------- | --------------- | --------- |
 | Set Power Level | ???            |                 |           |


#### Programming




#### References
Fan pinout
datasheets

#### Notes
MOSFET Array: (used to select which power to connect to TEC+/-
    - https://www.digikey.com/en/products/detail/sanken/SLA5085/4289314



Interface
---------
   1. Power switch
   2. 2x knobs with detent & push switch
   3. LCD display

Electronics
-----------
Display: https://www.sparkfun.com/products/16397
Knob: https://www.digikey.com/en/products/detail/kilo-international/OEDNI-63-2-7/5970329

**Rotary Encoder:**
We want a rotary encoder with detent & a momentary push switch. Probably want something with threads so that
it can be screwed onto the cover panel.

Options on Sparkfun:
   - https://www.sparkfun.com/products/9117
   - https://www.sparkfun.com/products/16879

**Power switch:**
Toddle switch. SPDT ON-ON or ON-OFF-ON or ON-NONE-ON

Options on Digikey:
   - https://www.digikey.com/en/products/detail/e-switch/100SP1T1B1M1QEH/378819

Options on Sparkfun:
   - https://www.sparkfun.com/products/9276



Humidity Element
-----------------


Box
----
Plastic: 1/8" or 1/4" Komatex PVC
   - 12.5" x 12.5" (2x)
   - 12" x 16" (3x)
   - clear door (polycarbonate)
   - https://www.tapplastics.com/
   - PVC Cement 
Door: 1/8" or 1/4" clear polycarbonate
   - 12" x 16"
   - https://www.tapplastics.com/
   - Fridge rubber seal
   - hinges
   - latch
Insulation
Wood
Cable Gland
Rack

Internal Dimensions
--------------------
12" x 12" x 16"



[TEC Block Diagram]: ./images/tec-controller-block-diagram.png
