
Technical capabilities of the system are as follows:

8 PWM capable channels with standard 3-pin headers, suitable for the MC29 and Servos in use today.
1 User programmable UART broken out to a standard 4 pin header (VCC, TX, RX, GND)
8 Digital I/O lines available for team use (limit switches, etc)
3 ADC lines available for team use (potentiometers)
Simple command interface for team code to poll the system processor for gamepad state – gamepad state and how it gets to the brain are considered abstract items teams do not need to be aware of.

Hanging off the system processor the following equipment is also available:
Some LEDs
4 switches for configuring modes
6 GPIO lines on 3 pin headers

The main board should accept 7.2v (nominal) power and convert this down to the 5V needed for the rpi onboard PSU.  Power available at the PWM headers is unregulated (but switched) 7.2v VBAT.  Power at the UART rail is the regulated power.  Power on the Digital and Analog I/O is VSYS from the pi the signal line is connected to.

Visual Status is provided for:
System Power
Network Connectivity/watchdog
Team Processor Watchdog


