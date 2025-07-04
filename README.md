# 📲 RCS – Relay Control System
This project is designed to control relays via SMS, RF remote, environmental sensors, and timers, using an STM32 microcontroller. It combines multiple input methods to provide flexible and automated relay switching for home appliances or industrial devices.


## 💡 Features

- **RF Control**: Relay on/off via 433 MHz RF remote control 🔌

- **GSM Control**: Send SMS to turn relays on/off using the Quectel M66
GSM module 📱

- **Sensor-Based Control**: Uses AHT20 temperature and humidity sensor for relay control 🌡

- **Timer-Based Control**: Set relay schedules with DS3231 RTC for accurate timekeeping ⏰

- **Display Interface**: 4x20 character LCD to show system status, temperature, time, and relay states 🖥

- **EEPROM Storage**: Save settings and schedules in AT24C32 EEPROM 💾

- **Manual control**: Two Push Button for navigate menus and make settings 🕹

![RCS](Images/RCS(4).jpg)


### 📋 Additional Details:
| Component               | Specification                        |
|-------------------------|--------------------------------------|
| **Microcontroller**     | STM32G070CBT6                        |
| **Operating Frequency** | 64MHz                                |
| **Programming Language**| Embedded C                           |
| **IDE**                 | stm32cubeide                         |
| **PCB Design Software** | Altium Designer                      |
| **Version Control**     | Git, GitHub                          |
| **Communication Module**| GSM (Quectel MC66)                   |
| **Remote Control**      | RXB22 433 MHZ                        |
| **Display**             | Character LCD 20x4                   |
| **Output**              | Relay, SPDT 12V NT90TNC12CB 240V/30A |
| **Temperature Sensor**  | AHT20                                |
| **5V Regulator**        | TPS54302                             |
| **4V Regulator**        | TPS563249                            |
| **3.3V Regulator**      | TLV74333                             |


