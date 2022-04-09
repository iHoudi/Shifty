# Shifty
A simple 7-segment display utilizing a shift register and Arduino. 

# Goals

Version 1 Board:
 - Proof of concept.
 #### Outcome:
 - Janky and barely/partially works.
 - Poor connections and use of space.

Version 2 Board:
 - Added current limiting resistors on all segments as opposed to cathodes of digits.
 - Added DIP socket for the SN74HC595N shift register for reuse and replacement.
  
Version 3 Board:
 - Add LEDS to each output and signal input of the shift register. This will allow for a visual queue as to what the register is doing.
 - Add circuit for measuring voltage (0-5v)
 - Add circuit for measuring amperage
 - Possibly change to Transistors to sink current instead of current limiting resistors
 - Possibly add 9v battery power solution. Will probably need to step down to IC voltage range.
  
Version 4 Board:
 - Begin design of PCB.
 - Find better mounting solution for 7-segment display.
  
