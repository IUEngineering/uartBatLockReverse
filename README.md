# uartBatLockReverse
An attempt to reverse engineer the UART-commands needed to open an electronic battery lock. This lock was extracted from a demo/prototype sharing e-bike that my previous employer generosly gifted me. 

---

This repository consists of a bin file extracted from a microcontroller of an e-bike battry lock and an .svd file. 

The bin file was extracted using a [STLINK-V3](https://www.st.com/en/development-tools/stlink-v3set.html) modular in-circuit debugger and programmer for STM32/STM8. 
The .svd file was sourced from the offical Arm webiste. found [here](https://www.keil.arm.com/devices/stmicroelectronics-stm32g030f6px/features/).

MCU: [STM32G030F6](https://www.st.com/en/microcontrollers-microprocessors/stm32g030f6.html)
