# notes
date: 14/02/2024
GPIO-general purpose input output:

GPIOs generally used for;
           1.Reading digital signals
           2.issuing interrupts
           3.Generating triggers for external components

GPIO pin and GPIO port:
      it have input buffer and output buffer.

GPIO input mode with high impedance state:

1.After reset MCU default GPIO pins are Input
Mode

2.Default GPIO pins will be in High Z state or
Floating state

3.Neither high state or ground state
Keeping the pin in floating state lead to leakage
current,power consumption.

GPIO input mode with pull-up /pull-down state:
  * internal pull up
  * internal pull down.

GPIO output mode with open drain state:

1.Open-drain output configuration
is nothing but the top PMOS
transistor is deactivated

2.When the transistor is ON,
the pin pulled to the ground.

3.When the transistor is OFF,
the drain of the transistor will
be floating or open.

4.That’s the reason it is called an drain state.














   
