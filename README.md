# FPGA-Based Intelligent Dual Elevator Scheduling System with Fire Evacuation

## Overview
This project implements an intelligent dual elevator scheduling system on an FPGA using Verilog HDL. The system efficiently manages two elevators while providing a dedicated fire evacuation mode. Elevator status and events are transmitted to a PC through UART for real-time monitoring.

## Features
- Intelligent dual elevator scheduling
- Fire evacuation mode
- UART communication for real-time status monitoring
- Verilog HDL implementation
- Hardware implementation on FPGA
- Finite State Machine (FSM)-based control

## Hardware
- Xilinx Spartan-7 FPGA
- USB-UART interface

## Software & Tools
- Xilinx Vivado
- Verilog HDL

## Project Structure
```
├── top.v
├── elevator_controller.v
├── fire_evacuation.v
├── uart_tx.v
├── clock_divider.v
├── constraints.xdc
├── testbench.v
├── README.md
├── demo.mp4
```

## UART Output
The system transmits elevator status, floor information, and fire emergency events to a PC through a serial terminal using UART.

## Applications
- Smart buildings
- Embedded systems
- FPGA-based control systems
- Safety-critical automation

## Award
🏆 First Prize – FPGA-Based Intelligent Dual Elevator Scheduling System with Fire Evacuation

## Author
Harikrishnan J
