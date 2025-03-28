# 🚀 Cargo Weight Measurement System

## 📌 Overview
Users place the goods onto the load cell system to obtain the exact weight measurement.

## 🖥️ Peripheral Configuration
- **ADC**: Used between the **Loadcell** and **STM32F401RE** to convert analog weight signals to digital.
- **I2C**: Used for communication between **STM32F401RE** and **16x2 LCD** to display the measured weight.

## 📂 Project Structure
```
📦 Cargo-weight
┣ 📜 code.txt – Initial source code
┣ 📜 code(da chinh sua).txt – Modified and finalized source code
┣ 📜 liquidcrystal_i2c.c – LCD I2C library (C source file)
┣ 📜 liquidcrystal_i2c.h – Header file for LCD I2C library
┣ 📜 README.md – Documentation and user guide
```

## ⚙️ How to Run the System
### 1️⃣ Required Hardware
- **STM32F401RE** microcontroller
- **Loadcell** with an **ADC interface**
- **16x2 LCD** connected via **I2C**

### 2️⃣ Steps to Run
1. Connect the **Loadcell** to STM32F401RE via **ADC**.
2. Connect the **16x2 LCD** to STM32F401RE via **I2C**.
3. Flash the compiled firmware onto STM32F401RE using **Keil** or **STM32CubeIDE**.
4. Power on the system and place goods on the Loadcell.
5. The weight measurement will be displayed on the **16x2 LCD**.

## 📌 Expected Results
- When goods are placed on the Loadcell, the system will measure the weight accurately.
- The weight will be displayed on the **16x2 LCD** in real-time.


