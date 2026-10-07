# Hardware Specifications

## Power Architecture
* Input: 5V DC via USB-C (powered directly through XIAO dev board).
* Logic Level: 3.3V logic throughout all SPI and GPIO lines.

## Pinout Definitions
* TFT Display (SPI):
  * MOSI: GPIO 6
  * SCK:  GPIO 4
  * CS:   GPIO 7
  * DC:   GPIO 2
  * RST:  GPIO 1
    
* Peripherals:
  * Buzzer: GPIO 3 (PWM active audio tone)
  * Button 1 (Snooze): GPIO 0 (Internal Pull-Up)
  * Button 2 (Set/Menu): GPIO 5 (Internal Pull-Up)

## PCB Physical Dimensions
* Outline: 50 mm x 40 mm rectangular profile
* Hole Mounts: 4x M3 (3.2 mm diameter, 3.5 mm offset from edges)
