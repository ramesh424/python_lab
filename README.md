# python_lab

Python Program to blink LED 

Here's a step-by-step approach to create the program:

Set up your Raspberry Pi Zero: Make sure your Raspberry Pi Zero is set up with the latest version of Raspberry Pi OS and is connected to the internet. You'll also need to enable the GPIO interface if it's not already enabled.

Connect the LED: Connect the long leg (anode) of the LED to a GPIO pin (for example, GPIO 17) and the short leg (cathode) to a ground (GND) pin on the Raspberry Pi through a resistor (220Ω to 1kΩ, to limit the current).

Install the RPi.GPIO library (if not already installed): This can be done using pip. Run sudo pip3 install RPi.GPIO in the terminal.

Write the blinking LED program: You'll write a Python script that turns the LED on and off in a loop.

