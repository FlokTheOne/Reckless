# Song Lyrics Display on LCD (I2C)

This project is a simple Arduino program that displays the lyrics of a song on a 16x2 LCD screen using the I2C communication protocol. The program cycles through different lines of lyrics on the screen, showing each line for a few seconds before updating to the next.

## Features

- Displays song lyrics on a 16x2 I2C LCD screen.
- Allows you to cycle through multiple lines of lyrics.
- The lyrics are shown line by line, with a delay between transitions.
- Uses simple button input to control the display if desired (though this is optional and can be customized).

## Requirements

To run this project, you'll need the following:

### Hardware:
- Arduino board (e.g., Arduino Uno, Nano, etc.)
- 16x2 LCD screen with I2C interface
- Push button (optional, for controlling song lyrics changes)
- Jumper wires for connecting the button and LCD to the Arduino

### Software:
- Arduino IDE
- **Adafruit LiquidCrystal** library for I2C LCD control
  - You can install this from the Arduino Library Manager.

## Wiring

1. **16x2 I2C LCD**:
   - **VCC** to 5V (or 3.3V depending on your LCD)
   - **GND** to GND
   - **SDA** to A4 (on Arduino Uno) or the corresponding SDA pin on your board
   - **SCL** to A5 (on Arduino Uno) or the corresponding SCL pin on your board

2. **Push Button (optional)**:
   - One side of the button goes to a digital pin (e.g., pin 2) on the Arduino.
   - The other side goes to GND. If you're using an internal pull-up resisto
