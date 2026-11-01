# Intro to Embedded

This repository contains the presentation materials for the Intro to Embedded Systems workshop conducted on 10/8/2026.

### Workshop Overview

The workshop is a beginner friendly introduction to embedded systems, the small computers hiding inside everything from microwaves to cars to game controllers. Attendees programmed an ESP32 with the Arduino IDE. It has five parts:

1. What Is Embedded?: what embedded systems are and why they're everywhere.
2. Build It: GPIO pins, LEDs, breadboards, and wiring the first LED circuit.
3. Talk to the Chip: writing and uploading the first programs, starting with Blink.
4. Add an Input: a button with INPUT_PULLUP, Serial output, and debouncing.
5. Level Up: non-blocking timing with millis(), PWM brightness, challenges, and a first look at WiFi.

### Setup

Install the [Arduino IDE](https://www.arduino.cc/en/software), then add ESP32 support. In Preferences (Settings on Mac), add this to Additional boards manager URLs:

```
https://espressif.github.io/arduino-esp32/package_esp32_index.json
```

Then install "esp32" from the Boards Manager.

---

_Note: The full slide content and presentation details can be found within this repo._
