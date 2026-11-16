# Firmware

Place the Arduino sketch for the Touch-To-Talk prototype in this folder, e.g.:

```text
firmware/
└── TouchToTalk/
    └── TouchToTalk.ino
```

## Target
- **Board:** Arduino Nano
- **Processor:** ATmega328P
- **Peripherals:** 3 × touch sensor, pulse sensor, I²C LCD, APR33A3 voice module, buzzer

## Behaviour the sketch implements
| Event | LCD | Voice (APR33A3) | Buzzer |
|---|---|---|---|
| Touch sensor 1 | `TAKE ME OUT` | ✅ | — |
| Touch sensor 2 | `EMERGENCY HELP` | ✅ | — |
| Touch sensor 3 | `I AM THIRSTY` | ✅ | — |
| BPM < 60 | `Heartbeat LOW` | — | ✅ |
| 60 ≤ BPM ≤ 100 | `Heartbeat NORMAL` | — | — |
| BPM > 100 | `Heartbeat HIGH` | — | ✅ |

## Pin mapping
Add a table here documenting which Nano pin connects to each module.
