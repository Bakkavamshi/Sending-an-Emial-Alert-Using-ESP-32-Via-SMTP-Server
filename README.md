# ESP32 Email Alert System

This project demonstrates how to send an email alert using an ESP32 microcontroller via an SMTP server. 

## Features
- Sends emails using ESP-Mail-Client library.
- Supports secure connections via SSL.
- Configurable for any SMTP provider (e.g., Gmail, Outlook).

## Requirements
1. ESP32 board.
2. Arduino IDE with ESP32 board support installed.
3. ESP-Mail-Client library.

## Steps to Use
1. Clone this repository.
2. Open `ESP32_Email_Alert.ino` in Arduino IDE.
3. Update your Wi-Fi and email credentials in the code.
4. Flash the ESP32 with the code.
5. Monitor the serial output for status.

## Libraries Required
- **ESP-Mail-Client**: Install via Arduino Library Manager.

## SMTP Provider Settings
| Provider  | Host             | Port |
|-----------|------------------|------|
| Gmail     | smtp.gmail.com   | 465  |
| Outlook   | smtp.office365.com | 587  |

## Demo
The ESP32 connects to Wi-Fi and sends an email alert to the configured recipient.
