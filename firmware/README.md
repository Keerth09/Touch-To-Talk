# Firmware

The Arduino firmware and pin-level wiring for the Touch-To-Talk prototype are **not publicly released**.

## Target
- **Board:** Arduino Nano (ATmega328P)
- **Peripherals:** 3 × touch sensor, pulse sensor, I²C LCD, APR33A3 voice module, buzzer

## Behaviour implemented
| Event | LCD | Voice (APR33A3) | Buzzer |
|---|---|---|---|
| Touch sensor 1 | `TAKE ME OUT` | ✅ | — |
| Touch sensor 2 | `EMERGENCY HELP` | ✅ | — |
| Touch sensor 3 | `I AM THIRSTY` | ✅ | — |
| BPM < 60 | `Heartbeat LOW` | — | ✅ |
| 60 ≤ BPM ≤ 100 | `Heartbeat NORMAL` | — | — |
| BPM > 100 | `Heartbeat HIGH` | — | ✅ |

For access requests, contact: keerthanak93987@gmail.com