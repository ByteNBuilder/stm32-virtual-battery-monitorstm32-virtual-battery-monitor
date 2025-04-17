# STM32 Virtual Battery Voltage Monitor 🔋

This is a minimalist STM32 embedded project that simulates a simple battery voltage monitor, built to run in **Renode** — no physical hardware required!

## 🧠 What It Does

- Simulates a microcontroller printing a voltage like `V:3.7V` over UART
- Compiled for STM32F4 (bare-metal)
- Tested using Renode's virtual platform

## 🛠️ Tools Used

- `arm-none-eabi-gcc` (to compile)
- `Renode` (to simulate STM32)
- `C`, `Makefile`, and no HAL/LL libraries — pure bare-metal register programming

## 📦 Folder Structure

- `src/` — Source files: `main.c`, `startup.s`, linker script
- `renode/` — Platform config for Renode
- `build/` — Compiled `.elf` files go here
- `Makefile` — To build everything easily
- `.gitignore` — Ignore compiled files and build artifacts

## 🚀 Running the Project


