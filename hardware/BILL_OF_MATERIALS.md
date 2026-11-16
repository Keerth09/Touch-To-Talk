# Touch to Talk: Hardware Bill of Materials (BOM)

This document specifies all components, modules, sensors, and power units required to construct the Touch to Talk system[cite: 1, 4].

## 1. Core Microcontroller & Power

| Item | Component Description | Specifications / Model | Quantity | Purpose |
| :--- | :--- | :--- | :--- | :--- |
| **1** | Microcontroller Board | Arduino Nano v3.0 (ATmega328P @ 16MHz) | 1 | Central Processing Unit[cite: 1, 4] |
| **2** | Power Supply | 5V DC 2A Regulated Adapter / USB Power | 1 | Regulated System Voltage Supply[cite: 3, 4] |

## 2. Input Sensors

| Item | Component Description | Specifications / Model | Quantity | Purpose |
| :--- | :--- | :--- | :--- | :--- |
| **3** | Capacitive Touch Sensor | TTP223 Digital Touch Module | 3 | Patient tactile message input[cite: 4, 5] |
| **4** | Pulse Heartbeat Sensor | Optical PPG Heart Rate Module (5V Analog) | 1 | Real-time cardiac pulse tracking[cite: 4, 6] |
| **5** | Temperature Sensor | LM35 Precision Centigrade Sensor | 1 | Body temperature monitoring[cite: 4] |
| **6** | IR Pair | 38kHz IR Receiver + 940nm IR Transmitter LED | 1 Set | Proximity / obstacle detection[cite: 4] |

## 3. Output & Alert Modules

| Item | Component Description | Specifications / Model | Quantity | Purpose |
| :--- | :--- | :--- | :--- | :--- |
| **7** | Character LCD | 16x2 Green Backlight Character Display | 1 | Visual message & pulse display[cite: 4, 5] |
| **8** | I2C Serial Interface | PCF8574 I2C Backpack Module | 1 | Reduces LCD pin count to SDA/SCL[cite: 3, 4] |
| **9** | Voice Playback Module | APR33A3 8-Channel Rec/Playback Module | 1 | Multi-channel audio voice output[cite: 1, 4] |
| **10**| Audio Speaker | 8 Ohm, 0.5W Dynamic Speaker | 1 | Caregiver acoustic voice output[cite: 4, 5] |
| **11**| Acoustic Alarm | 5V Active Electromagnetic Piezo Buzzer | 1 | Bradycardia / Tachycardia alert[cite: 4, 6] |