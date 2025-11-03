# 💡 Microcontroller I/O and LCD Display (HCS12)

A project for the **HCS12 microcontroller** demonstrating how to interface with and program input/output devices — including switches, LEDs, a keypad, a buzzer, and an LCD display.

## 🧩 Overview
This project explores **data exchange between a microprocessor and external devices**, combining low-level hardware control with software design.  
It builds from basic digital I/O to a complete LCD display program.

## ⚙️ Features
- Software delay loops for timing control  
- Bit masking operations for register manipulation  
- Reading input from switches and keypads  
- Controlling output devices: LED bar, RGB LED, buzzer  
- Displaying text and hexadecimal values on an LCD module  

## 🧠 Concepts Demonstrated
- Microcontroller I/O programming  
- Hardware interfacing using registers and ports  
- Bitwise operations (AND, OR, EOR)  
- ASCII conversion and string display on LCD  
- Modular subroutine design (`putcLCD`, `putsLCD`, `initLCD`, etc.)

## 🚀 How to Run
1. Assemble and load the code onto the **HCS12 or EvalH1 trainer board**.  
2. Observe:
   - Switch states reflected on LED bar  
   - Keypad controlling RGB LED colors  
   - Buzzer tone generation using delay loops  
   - LCD showing text + hexadecimal values from memory (`$3000` and `$3001`)  

## 💡 Highlights
- Excellent introduction to **embedded systems programming**  
- Combines both hardware and software-level design  
- Forms a foundation for advanced microcontroller projects
