# RP2040-Flight-Computer
This is a custom drone flight computer based on RP2040. The KiCad files are available in addition to the production files to be produced by JLC PCB.

The Flight computer has the following sensors:
  - MPU 6050 Inertia sensor
  - HMC5883L digital compass sensor
  - BMP280 pressure sensor

Other specified connectors that can be added:
  - SD-card connector at the bottom of the board
  - Two uart connectors for the Radio controller (tagged IBUS) and another for GPS (tagged GPS)
  - Broken GPIOs for NRF24L01 with proper pin locations

Additionally, the two I2C ports connected to the MPU6050 and BMP280 have the pins exposed for debugging purposes.

The board was produced and assembled by JLCPCB and working.


![RP2040-Brain-v2 0](https://github.com/aliismail92/RP2040-Flight-Computer/assets/14983451/049a41d5-8ba0-456a-9837-c261d88a136e)
