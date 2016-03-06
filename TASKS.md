This is a simple task tracking in a single textfile.

# TODO

- Sketch VOX version of circuit in Eagle
- Toggle pin high/low with command over keyboard or USB serial
- Determine circuit implementation details:
  - Transistor as a switch - possibly also use relay?
- Disassemble handset to see if it has any internal circuitry to be aware of for PTT switch
- Purchase prototype parts
- Build breadboard version of circuit
- Build perfboard version of circuit
- Learn how to make Gerber files in Eagle
- Determine BOM & order
- Assemble + reflow PCB version of circuit
- Modify APRSDroid to toggle PTT
- Antenna work

# In Progress

- Set up microcontroller as USB serial - echo back received character offset by 1

# Done

- Solder TRRS -> 0.1" header
- Solder Baofeng headset plug -> 0.1" header
- Determine circuit implementation details:
  - Transistor as switch any complexity with no common ground?  
  - Transformer values (i.e. output voltage of Baofeng HT & mobile phone vs. expected input voltages)
  - Possibly build voltage divider version?  Any risks with this approach?
  - Notes: it looks like the isolation transformers are not necessary in this case, a simpler voltage divider approach should work, moved related tasks to done
- Breadboard VOX version of circuit w/ voltage dividers
  - Notes: took resistor/capacitor values from: [this cool writeup](http://www.creativedistraction.com/demos/sensor-data-to-iphone-through-the-headphone-jack-using-arduino/)
- Flash ATmega16U with anything, reflash with original firmware to verify board won't be bricked
  - Notes: used an ArduinoISP for this
