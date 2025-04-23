# STM32 I2C LCD Display Project

This project demonstrates how to interface a **16x2 I2C LCD** (using PCF8574) with an **STM32L4** microcontroller using **STM32CubeIDE** and the HAL library.

## 📌 Features
- I2C communication with 16x2 LCD
- Display custom messages (temperature, humidity, etc.)
- Compatible with popular LCD backpack (I2C address 0x27 or 0x4E)

## 🧰 Hardware Used
- STM32 B-L475E-IOT01A board
- 16x2 LCD with I2C backpack (PCF8574)
- Optional: Sensors for data (HTS221, MLX90614, etc.)

## 🔌 Connections
| LCD Pin | Function      | STM32 Pin |
|---------|---------------|-----------|
| VCC     | Power         | 3.3V      |
| GND     | Ground        | GND       |
| SDA     | I2C Data      | PB9       |
| SCL     | I2C Clock     | PB8       |

> Note: These pins depend on your CubeMX configuration.

## 🛠️ How to Build
1. Open the project in STM32CubeIDE.
2. Connect your board.
3. Build & flash the firmware.
4. You should see the message displayed on the LCD.

## 📄 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
