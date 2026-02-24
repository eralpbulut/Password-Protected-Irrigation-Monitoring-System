# Password-Protected Irrigation Monitoring System (FRDM-KL25Z)

This project implements a real-time embedded irrigation monitoring system using the FRDM-KL25Z microcontroller. The system monitors soil moisture, light conditions, and rain status while providing a password-protected user interface with LCD display and keypad input.

## Features

- Password-protected system access using 4×4 keypad
- Real-time soil moisture measurement using ADC
- Light sensor with interrupt-based detection
- Rain detection with digital input
- 16×2 LCD user interface with multiple display modes
- Audible buzzer alerts for critical conditions
- Interrupt-driven firmware design
- State-based embedded system architecture

## Hardware

- FRDM-KL25Z (ARM Cortex-M0+) microcontroller
- 16×2 HD44780 LCD display (4-bit mode)
- 4×4 keypad for password entry
- Soil moisture sensor (analog input)
- Light sensor (interrupt input)
- Rain sensor (digital input)
- Buzzer for alerts
- Push button for screen control

## Software / Firmware Features

- SysTick timer for precise timing (1 ms resolution)
- Interrupt-based sensor handling
- ADC-based soil moisture measurement and calibration
- Password authentication system
- LCD driver implemented in C
- Non-blocking system design with real-time response
- Modular embedded firmware architecture

## Results

- Successful password-protected system operation
- Real-time monitoring of environmental conditions
- Reliable interrupt handling and sensor integration
- Responsive LCD interface and alert system
- Stable and reliable embedded system performance

## Report

📄 [View Full Project Report](EEE212_Project_Report.pdf)

## Demo Video

▶️ https://www.youtube.com/watch?v=aw-JuuW3rH0

## Author

Mehmet Eralp Bulut  
Electrical and Electronics Engineering Student  
Bilkent University
