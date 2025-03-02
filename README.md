# ESP32 Email Alert System 🚀

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

## Results 🎯
The ESP32 Email Alert system was successfully implemented with the following outcomes:

1. **Wi-Fi Connectivity**:  
   - The ESP32 connected to the configured Wi-Fi network and retrieved an IP address.
   
2. **SMTP Communication**:  
   - The ESP32 securely connected to the SMTP server (e.g., Gmail) using SSL/TLS.

3. **Email Delivery**:  
   - Emails were successfully sent to the specified recipient address.  
   - The email contained the configured subject, sender details, and body text.

4. **Debug Output**:  
   - Serial Monitor displayed connection status, logs, and success/error messages.

### 📹 Demo Video  
**Watch the demo here:**  
[📺 Click to Watch](video/video_2025-03-02_14-50-49.mp4)  

---

### **Project Structure**
