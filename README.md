# Custom ESP32-S3 Development Board with USB-C

This repository features a custom ESP32-S3 development board designed for IoT, embedded systems, and prototyping needs.

## Features

- **Microcontroller:** ESP32-S3 Mini
- **Dual USB-C Ports:**
  - **USB1:** For UART communication and flashing
  - **USB2:** Dedicated power input (5V)
- **Buttons:**
  - **BOOT/USER Button:** Configurable for user input or boot mode
  - **RESET Button:** For resetting the module
- **Voltage Regulators:** Onboard 3.3V and 5V outputs
- **Breadboard-Compatible:** Easy access to GPIO pins
- **LED Indicators:** Power and status LEDs for easy debugging

## Applications

- IoT projects  
- Smart home automation  
- Sensor interfacing  
- Embedded systems prototyping  

## Getting Started

1. **Connect the Board:**
   - Use USB-C for power or programming.
2. **Development Environment:**
   - Set up your preferred IDE (e.g., [Arduino IDE](https://www.arduino.cc/en/software), [PlatformIO](https://platformio.org/), or [ESP-IDF](https://github.com/espressif/esp-idf)).
3. **Flashing Firmware:**
   - Hold the **BOOT/USER button** and press the **RESET button** to enter flashing mode.
   - Upload your firmware using tools like `esptool.py`.
4. **Reference Pinout:**
   - Check the `docs/` folder for the GPIO pinout and other reference materials.
5. **Gerber Files**
   - Check the `Project Outputs for ESp_32/` folder for the Gerber Files for the Board.


## Repository Structure

- `design/` - PCB and schematic design files (Altium Designer format)
- `firmware/` - Example firmware for testing the board
- `docs/` - Documentation and resources

## Preview


### Front View
![ESP32-S3 Board Front](https://github.com/Kaushikgupta469/ESP32-Custom_Board/blob/main/Images/Front.png)

### Back View
![ESP32-S3 Board Back](https://github.com/Kaushikgupta469/ESP32-Custom_Board/blob/main/Images/Back.jpg)

## Applications
- IoT Development

# Feel free to explore, contribute, or suggest improvements!  




