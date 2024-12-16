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

## Result
The ESP32 Email Alert system was successfully implemented with the following outcomes:

1. **Wi-Fi Connectivity**: 
   - The ESP32 was able to connect to the configured Wi-Fi network and retrieve an IP address.
   
2. **SMTP Communication**:
   - The ESP32 securely connected to the SMTP server (e.g., Gmail) using SSL/TLS protocols.
   
3. **Email Delivery**:
   - Emails were successfully sent to the specified recipient address.
   - The email contained the configured subject, sender details, and body text.
   
4. **Debug Output**:
   - Serial Monitor displayed connection status, debug logs from the ESP-Mail-Client library, and success/error messages for email transmission.

## Conclusion
The ESP32 Email Alert project demonstrates how to use the ESP32 microcontroller for sending automated email notifications. This can be extended for applications such as:

- Real-time alerts from IoT sensors (e.g., temperature, motion, or humidity).
- Remote monitoring and control systems.
- Emergency notifications.

The project is flexible and can be configured with any SMTP provider by updating the server details, making it adaptable for various use cases in IoT and embedded systems.
