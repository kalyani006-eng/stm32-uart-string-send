# STM32 UART String Send Example

This project demonstrates how to send a string over UART using STM32F103C8T6 and the HAL library.

## 📦 Features
- Sends `"Hello via UART"` continuously over USART1
- Baud Rate: `115200`
- Uses `HAL_UART_Transmit()` inside `main()`

## 🔧 Hardware
- MCU: STM32F103C8T6 (Blue Pill)
- TX Pin: PA9
- RX Pin: PA10

## 🛠 Tools Used
- STM32CubeIDE
- HAL Drivers

## 📂 Project Files
- `Core/` – main source files
- `Drivers/` – HAL libraries
- `.ioc` – STM32CubeMX configuration file

## 🔁 Output (Serial Monitor)
