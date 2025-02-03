# STM32-Nucleo-H743ZI2-Projects

Welcome to the **STM32-Nucleo-H743ZI2-Projects** repository! This repository is dedicated to exploring and utilizing the capabilities of the **ST Nucleo-H743ZI2** development board. Here, you'll find a collection of projects, examples, and resources that will help you get the most out of this high-performance microcontroller. This repository serves as my playground to experiment with various embedded systems applications.

![STM32 Nucleo H743ZI2](https://www.st.com/en/evaluation-tools/nucleo-h743zi.html)

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Projects](#projects)
  - [GPIO (LED Blink, Button)](#gpio)
  - [UART Communication](#uart-communication)
  - [PWM Generation](#pwm-generation)
  - [ADC and Sensor Integration](#adc-and-sensor-integration)
  - [Timers](#timers)
  - [SPI and I2C](#spi-and-i2c)
  - [RTOS-Based Applications](#rtos-based-applications)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The **STM32H743ZI2** is a high-performance microcontroller from STMicroelectronics, built for real-time processing, industrial applications, and embedded control. This repository provides structured examples covering various peripherals and real-world applications.

## Getting Started
To get started with the projects in this repository, you'll need the following tools and software:

- **STM32CubeIDE**: The recommended integrated development environment (IDE) for STM32 projects.
- **STM32CubeMX**: A tool for generating initialization code and configuring peripherals.
- **GNU ARM Toolchain**: Required for compiling the firmware.
- **ST-Link Utility**: Used for flashing and debugging.
- **PlatformIO (Optional)**: Alternative IDE for embedded development.

### Installation Steps
1. Download and install [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html).
2. Install [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html) for peripheral configuration.
3. Set up the [GNU ARM Toolchain](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain).
4. Install the [ST-Link Utility](https://www.st.com/en/development-tools/stsw-link004.html) for flashing firmware.

## Repository Structure

```
STM32-Nucleo-H743ZI2-Projects/
│── 01-GPIO/
│    ├── LED_Blink/
│    ├── Button_Interrupt/
│── 02-UART/
│── 03-PWM/
│── 04-ADC/
│── 05-TIMERS/
│── 06-SPI_I2C/
│── 07-RTOS/
│── docs/
│── README.md
│── LICENSE
```

### Projects

#### GPIO
- **[LED Blink](01-GPIO/LED_Blink)** - A basic example to toggle an LED.
- **[Button Interrupt](01-GPIO/Button_Interrupt)** - Using an external button as an interrupt.

#### UART Communication
- **[Basic UART](02-UART/Basic_UART)** - Sending and receiving data over serial communication.
- **[UART with DMA](02-UART/UART_DMA)** - Optimized data transmission using DMA.

#### PWM Generation
- **[PWM Signal](03-PWM/PWM_Signal)** - Generating PWM output.
- **[Servo Motor Control](03-PWM/Servo_Control)** - Controlling a servo using PWM.

#### ADC and Sensor Integration
- **[Analog Read](04-ADC/ADC_Read)** - Reading sensor data using ADC.
- **[ADC with DMA](04-ADC/ADC_DMA)** - Using DMA for efficient ADC data acquisition.

#### Timers
- **[Timer Interrupt](05-TIMERS/Timer_Interrupt)** - Using timers for periodic interrupts.
- **[Input Capture](05-TIMERS/Input_Capture)** - Measuring external signal frequencies.

#### SPI and I2C
- **[SPI Communication](06-SPI_I2C/SPI_Master)** - Setting up SPI for data transfer.
- **[I2C Communication](06-SPI_I2C/I2C_Master)** - Interfacing with I2C peripherals.

#### RTOS-Based Applications
- **[FreeRTOS Multitasking](07-RTOS/FreeRTOS_Tasks)** - Running multiple tasks in parallel.
- **[RTOS Synchronization](07-RTOS/RTOS_Sync)** - Using semaphores and mutexes.

## Resources
- [STM32H743ZI2 Datasheet](https://www.st.com/resource/en/datasheet/stm32h743zi.pdf)
- [STM32CubeH7](https://www.st.com/en/embedded-software/stm32cubeh7.html)
- [STM32 Reference Manual](https://www.st.com/resource/en/reference_manual/dm00314099-stm32h742-h743-753-and-h750-value-line-advanced-armbased-32bit-mcus-stmicroelectronics.pdf)
- [ST Community Forum](https://community.st.com/s/)
- [STM32 GitHub Repositories](https://github.com/STMicroelectronics)
- [RTOS for STM32](https://www.freertos.org/RTOS.html)
- [PlatformIO STM32 Support](https://docs.platformio.org/en/latest/platforms/ststm32.html)

## Contributing
Contributions are welcome! If you have a project or example you'd like to share, please fork the repository, create a new branch, and submit a pull request. Ensure that you follow best coding practices and include a README.md with your submission.

## License
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

Happy coding! 🚀

**Kiran Jojare**  
*Embedded Software / Firmware Engineer*  
kijo7257@colorado.edu
