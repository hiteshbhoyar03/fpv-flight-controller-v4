# FPV Flight Controller v4

<p align="center">
  <img width="39%" src="https://github.com/hiteshbhoyar03/fpv-flight-controller-v4/blob/main/gallery/fpv%20fc%20front.png">
  <img width="39%" src="https://github.com/hiteshbhoyar03/fpv-flight-controller-v4/blob/main/gallery/fpv%20fc%20back.png">
</p>

This is the FPV Flight Controller v4, designed for high-performance multirotor and experimental UAV platforms.

Built around the STM32H743 microcontroller, the board integrates multiple IMUs, dual barometers, external flash memory, CAN communication, and extensive I/O.

Project status: ongoing development.  
Hardware fabrication and testing will be carried out later.

---

## Learning Objectives

- Redundant IMU and barometer architectures  
- STM32H7-based flight control systems  
- FPV interfaces including PWM, SBUS, UART, and CAN  
- Sensor power integrity  
- External flash blackbox logging  

---

## Key Features

- STM32H743 MCU  
- Dual BMI088 IMUs  
- ICM-42688P IMU  
- Dual BMP390 barometers  
- BMM350 magnetometer  
- 12 PWM outputs  
- SBUS receiver support  
- 5 external UARTs  
- CAN interface  
- USB Type-C  
- External SPI flash  
- 39 mm × 39 mm PCB  

---

## Sensor Architecture

IMUs  
- BMI088 ×2  
- ICM-42688P  

Environmental sensors  
- BMP390 ×2  
- BMM350  

---

## Microcontroller

- STM32H743VIT6  
- ARM Cortex-M7  
- 480 MHz  
- FPU and DMA support  

---

## Interfaces

| Interface | Details |
|----|----|
| UART ×5 | External communication |
| I2C ×1 | Sensor interface |
| CAN | TCAN337G |
| USB-C | Configuration |
| PWM ×12 | ESC and servo |
| SBUS | RC input |

---

## Memory

- W25Q128JVPIQ SPI flash  
- Used for blackbox logging and fault analysis  

---

## Power Architecture

| Rail | Component |
|----|----|
| Main buck | TPS62933 |
| 3.3 V LDO | LP5912-3.3 |

---

## Mechanical Specifications

| Parameter | Value |
|----|----|
| Dimensions | 39 mm × 39 mm |
| Connectors | SM08B-SRSS |
| PWM | Connector and pads |
| UARTs | External |

---

## Author

Hitesh Bhoyar  
Embedded Systems | UAV Electronics  
https://github.com/hiteshbhoyar03

---

## License

MIT License
