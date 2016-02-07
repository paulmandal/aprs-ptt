This is a simple task tracking in a single textfile.

# TODO

- Flash ATmega16U with anything, reflash with original firmware to verify board won't be bricked
- Set up microcontroller as USB keyboard or serial
- Toggle pin high/low with command over keyboard or USB serial
- Determine circuit implementation details:
  - Transistor as a switch - possibly also use relay?
- Purchase prototype parts
- Build breadboard version of circuit
- Build perfboard version of circuit
- Learn how to make Gerber files in Eagle
- Determine BOM & order
- Assemble + reflow PCB version of circuit
- Modify APRSDroid to toggle PTT
- Antenna work

# In Progress

- Breadboard VOX version of circuit w/ voltage dividers

# Done

- Solder TRRS -> 0.1" header
- Solder Baofeng headset plug -> 0.1" header
- Determine circuit implementation details:
  - Transistor as switch any complexity with no common ground?  
  - Transformer values (i.e. output voltage of Baofeng HT & mobile phone vs. expected input voltages)
  - Possibly build voltage divider version?  Any risks with this approach?
  - Notes: it looks like the isolation transformers are not necessary in this case, a simpler voltage divider approach should work, moved related tasks to done
