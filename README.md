# Wearable Health Monitoring System

## 📘 Overview
This project is a secure, real-time wearable device built using the STM32F405 microcontroller to monitor vital health parameters such as heart rate, SpO2, and body temperature.

## 🧠 Features
- Heart rate and SpO2 sensing via MAX30102
- Non-contact body temperature measurement
- Password-protected system access
- LCD and 7-segment display outputs
- RGB LED and LED bar graph for health status
- Buzzer for abnormal condition alerts
- 4x4 keypad input interface
- EEPROM-based password storage
- Powered using a buck converter

## 🔧 Hardware Requirements
- STM32F405RGT6 Board
- MAX30102 Heart Rate & SpO2 Sensor
- Non-contact IR Temperature Sensor
- 4-Digit 7-Segment Displays (x2)
- 16x2 LCD Display
- RGB LEDs and Bar Graph LED
- Buzzer
- 4x4 Matrix Keypad
- SPI EEPROM
- Buck Converter

## 🧑‍💻 Software Requirements
- STM32CubeIDE
- STM32 HAL Drivers
- FreeRTOS (optional for task scheduling)

## 🚦 System Flow
1. Power ON → LCD: "Welcome"
2. Press '*' → Enter password
3. If matched:
   - "Access Granted" → Green LED ON
   - Menu: Start Monitoring or Change Password
4. On Monitoring:
   - Read HR, SpO2, Temp
   - Display values
   - Trigger buzzer and alert LEDs if abnormal

## 📊 Display & Alerts
- HR & SpO2: 7-Segment Displays
- Temp: LCD
- Status: LED Bar Graph
- Buzzer + Red/Green LEDs for alerts

## 🔐 Security
- 4-digit code entry via keypad
- Stored securely in SPI EEPROM
- Password change functionality available

## 👨‍🔧 Authors
- Ayushi Jaiswal
- Sreekumar Adithya
- Amal Viswam
- Shubham Anil
- Tawfeeq

## 📍 Institution
Bosch Global Software Technologies, Hyderabad – July 2025

## 📎 License
This project is licensed for academic and personal research use.

---

*Designed for wearable health applications with embedded system precision and real-time feedback.*
