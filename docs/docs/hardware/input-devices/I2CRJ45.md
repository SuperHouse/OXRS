---
tags: ["I2CRJ45", "URC", "I2CRJ45"]
---
# I2CRJ45
<p class="maker">by <b>SuperHouse Automation</b></p>

<!-- Board Image -->
![SuperHouse Automation I2CRJ45x8 board](/images/i2crj45.jpg)
<!-- ![SuperHouse Automation I2CRJ45x8 board](/images/oxrs-I2CRJ45X8.jpg) -->
<!-- ![SuperHouse Automation I2CRJ45x16 board](/images/oxrs-I2CRJ45X16.jpg) -->
<!-- ![SuperHouse Automation I2CRJ45x24 board](/images/oxrs-I2CRJ45X24.jpg) -->
<!-- ![SuperHouse Automation I2CRJ45x24 board](/images/oxrs-I2CRJ45X32.jpg) -->

<!-- Board Description -->
I2C compatible board that handles multiple inputs via a RJ45 connection The RJ45 sockets on the breakout are connected to I/O channels via I2C addressable I/O buffers. Each RJ45 socket provides connections for GND, 12V, and 4 signal lines.

## Features
- Comes in 8, 16, 24 and 32 port versions
- MCP23017 I2C I/O drivers
- I2C headers for connection to host control board
- Firmware supports multiple types of switches, contacts, encoders
- 12-24v DIY POE on the RJ45 connections for switches with basic LEDs
- 4 i/o connections per RJ45 port

## Supported Firmware
- OXRS State Monitor ESP32 [OXRS-SHA-StateMonitor-ESP32](/docs/firmware/state-monitor-esp32.md)
- OXRS State Controller ESP32  [OXRS-SHA-StateController-ESP32](/docs/firmware/state-controller-esp32.md)
- OXRS State IO ESP32 [OXRS-SHA-StateIO-ESP32-FW](/docs/firmware/state-io-esp32.md)

::: tip
The State IO ESP32 firmware combines the functionality of both the [OXRS-SHA-StateMonitor-ESP32](/docs/firmware/state-monitor-esp32.md) and [OXRS-SHA-StateController-ESP32](/docs/firmware/state-controller-esp32.md) firmware in the one package.
:::

- OXRS Smoke Detector ESP32 [OXRS-SHA-SmokeDetector-ESP32-FW](/docs/firmware/smoke-detector-esp32.md)
- OXRS-IO-SecurityMonitor-ESP32-FW [Github](https://github.com/austinscreations/OXRS-AC-SecurityMonitor-ESP32-FW)

## Additional Resources
- More info [Github](https://github.com/SuperHouse/I2CRJ45)

## Where to Buy
- [SuperHouse Store](https://www.superhouse.tv/product/i2c-rj45-light-switch-breakout/)

## FAQs
::: details Does it come with a power supply?
The 12V and 3.3V power requirements of the I2CRJ45 are intended to be supplied via the I2CBR 6 Pin Header ribbon cable connection from the associated controller board, which would either be a Rack32 [Link](/docs/hardware/controllers/rack32.md) PCB or a more recent 3rd party developed control board such as Austin Creation's OXRS-Black [Link](docs/hardware/controllers/oxrs-black.md) PCB.
:::

::: tip Maker Info
**Maker:** SuperHouse Automation

**Link:** [https://www.superhouse.tv](https://www.superhouse.tv)
:::

## Compatible With
- Rack32 [Link](/docs/hardware/controllers/rack32.md) **<-- Best Choice**
- OXRS-Black [Link](docs/hardware/controllers/oxrs-black.md)
- Room8266 [Link](/docs/hardware/controllers/room8266.md)
