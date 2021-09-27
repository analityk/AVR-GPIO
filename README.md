# AVR-GPIO
GPIO class for avr
For example:

GPIO led_pc2(&PORTC, PINC2);
GPIO pio1(&PORTB, PINB3);

{ ...
led_pc2.flip();
pio1.set();
pio1.clear();
... }
