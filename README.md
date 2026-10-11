# ESP32 Network Monitor (with LEDs)
A physical desk-side status dashboard for at-a-glance network monitoring and high nerd vibes. The ESP32 microcontroller checks a list of IP addresses and lights a bi-directional red/green LED for each: green when the device answers, red after two missed checks (and amber before its first check). Devices that ignore ping can be checked by TCP port instead. If the ESP32 loses WiFi, every LED blinks red.

Each LED is driven directly from two GPIO pins with a single resistor, so there's no multiplexing and no extra chips. An ESP8266 version is also possible using charlieplexing to run up to 15 LEDs from 6 pins.

# Wiring Diagram
Coming soon ...
