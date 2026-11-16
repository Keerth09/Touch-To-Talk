# Touch to Talk: Circuit Wiring & Pinout Guide

This document details the exact point-to-point pin connections between the Arduino Nano, input sensors, output displays, and voice modules[cite: 4].

## 1. Power Distribution Rail
- **Arduino 5V Pin** $\rightarrow$ System $+5\text{V}$ Power Rail
- **Arduino GND Pin** $\rightarrow$ System Common Ground (GND) Rail

## 2. Input Sensor Connections

### A. TTP223 Touch Sensor Modules (x3)
- **Touch Sensor 1 (Message: "TAKE ME OUT"):** VCC $\rightarrow$ $+5\text{V}$ | GND $\rightarrow$ GND | OUT $\rightarrow$ **Pin D2**[cite: 4, 5]
- **Touch Sensor 2 (Message: "EMERGENCY HELP"):** VCC $\rightarrow$ $+5\text{V}$ | GND $\rightarrow$ GND | OUT $\rightarrow$ **Pin D3**[cite: 4, 5]
- **Touch Sensor 3 (Message: "I AM THIRSTY"):** VCC $\rightarrow$ $+5\text{V}$ | GND $\rightarrow$ GND | OUT $\rightarrow$ **Pin D4**[cite: 4, 5]

### B. Optical Heartbeat Sensor
- VCC $\rightarrow$ $+5\text{V}$ Rail | GND $\rightarrow$ GND Rail | Signal (S) $\rightarrow$ **Analog Pin A0**[cite: 4, 6]

### C. Temperature Sensor (LM35)
- VCC $\rightarrow$ $+5\text{V}$ Rail | GND $\rightarrow$ GND Rail | OUT $\rightarrow$ **Analog Pin A1**[cite: 4]

## 3. Output Module Connections

### A. LCD Display with PCF8574 I2C Backpack
- VCC $\rightarrow$ $+5\text{V}$ Rail | GND $\rightarrow$ GND Rail
- SDA $\rightarrow$ **Pin A4** | SCL $\rightarrow$ **Pin A5**[cite: 3, 4]

### B. APR33A3 Voice Module & Speaker
- VCC $\rightarrow$ $+5\text{V}$ Rail | GND $\rightarrow$ GND Rail
- Channel M1 Trigger $\rightarrow$ **Pin D5** (Active LOW)[cite: 4, 5]
- Channel M2 Trigger $\rightarrow$ **Pin D6** (Active LOW)[cite: 4, 5]
- Channel M3 Trigger $\rightarrow$ **Pin D7** (Active LOW)[cite: 4, 5]
- Speaker Pins (+/-) $\rightarrow$ Directly connected to 8 Ohm Audio Speaker[cite: 4]

### C. Piezo Buzzer Alert System
- Positive Terminal (+) $\rightarrow$ **Pin D8** | Negative Terminal (-) $\rightarrow$ GND Rail[cite: 4, 6]