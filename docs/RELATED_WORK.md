# Related Work

Review of related systems and how Touch-To-Talk differs. Reference numbers match [REFERENCES.md](REFERENCES.md).

| Ref | Authors | Year | Title | Key findings | Limitations |
|---|---|---|---|---|---|
| [10] | S. Roy & S. K. Sharma | 2024 | Design and Implementation of an Arduino-Based Health Monitoring and Communication System for Paralyzed Patients | Arduino Nano system for real-time pulse tracking and local LCD-based messaging | No integrated voice-assisted feedback for non-visual caregiver alerts |
| [11] | B. G. Deepthi et al. | 2023 | Design of an IoT based smart health monitoring system for elderly and paralyzed patients | ESP8266 + sensors with a web-based dashboard for medical data | Complex user interface for patients with total paralysis |
| [12] | V. K. Sharma & R. Kumar | 2021 | IoT-Based Patient Health Monitoring System Using Arduino and ESP8266 | Robust framework for wireless data transmission with low-cost MCUs | Focuses on data transmission, not patient-initiated communication |
| [13] | S. Abdulmalek et al. | 2022 | IoT-Based Healthcare-Monitoring System towards Improving Quality of Life: A Review | Comprehensive analysis of biomedical sensors and IoT healthcare integration | Theoretical review; no custom hardware prototype for paralysis |
| [14] | M. N. Islam et al. | 2020 | An IoT-based patient monitoring system for paralyzed patients using ESP8266 and heartbeat sensors | Cloud-based monitoring of heartbeat variations with remote alerts | Depends heavily on stable internet for emergency notifications |
| [15] | R. P. Singh & M. Javid | 2022 | Internet of Things applications in the field of paralysis for better healthcare | Explores smart sensors for autonomy of physically challenged individuals | No specific circuit architecture for dual-mode (audio/visual) alerts |

## Gap addressed
Most existing systems do **either** communication **or** monitoring, are costly, or rely on internet connectivity. Touch-To-Talk integrates **touch-based patient communication (LCD + voice)** and **heart-rate alerting** in a single, low-cost, standalone Arduino Nano device suitable for homes and hospitals.
