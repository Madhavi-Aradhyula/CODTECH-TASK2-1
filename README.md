# 8-bit Arithmetic Logic Unit (ALU)

- **Name:** MADHAVI ARADHYULA  
- **Company:** CODTECH IT SOLUTIONS  
- **ID:** CT08DOW  
- **Domain:** VLSI  
- **Duration:** Dec 2024 to Jan 2024  
- **Mentor:** SRAVANI GOUNI

---

## Project Overview  
The **8-bit Arithmetic Logic Unit (ALU)** is a digital circuit designed to perform a variety of arithmetic and logical operations on 8-bit input values. This project uses Verilog, a hardware description language, to define the behavior of the ALU. The ALU can perform basic operations such as addition, subtraction, multiplication, division, and logical operations like AND, OR, XOR, and NOT. The design also includes a **Carry-Out** flag, which is crucial in arithmetic operations, especially for indicating overflow in addition.

The ALU operates based on a 4-bit control signal (`ALU_Sel`), which determines which operation is executed. A comprehensive **Testbench** has been created to simulate the functionality of the ALU and to generate **waveform files** (`.vcd`), which are useful for debugging and verifying the correctness of the design.

This project provides hands-on experience with **digital design principles**, **VLSI design**, and **simulation tools**, making it an essential learning exercise for anyone looking to understand the core concepts of hardware design.

---

## Features
- **Arithmetic Operations:**  
  - **Addition**, **Subtraction**, **Multiplication**, and **Division** on 8-bit input values.

- **Logical Operations:**  
  - **AND** (`A & B`), **OR** (`A | B`), **XOR** (`A ^ B`), and **NOT** (`~A`).

- **Carry-Out Flag:**  
  - The ALU computes a **CarryOut** flag for the addition operation to indicate overflow.

- **Testbench Simulation:**  
  - A testbench simulates various ALU operations, verifying the design and generating waveform files for visual inspection.

- **Modular and Reusable Design:**  
  - The ALU design is modular, enabling easy adaptation for different bit-widths or additional operations in future versions.

---

## Tools Used
- **Verilog:**  
  The ALU and its operations are described using **Verilog HDL**, a hardware description language for designing digital circuits.

- **EDA Playground:**  
  An online platform for simulating and running Verilog code. It is used here for simulating the ALU design and generating **.vcd** waveform files for analysis.

- **GTKWave:**  
  A waveform viewer used to visualize the **.vcd** files generated during simulation. It allows you to analyze the ALU's output and verify correctness.

---

## Simulation Results
![image](https://github.com/user-attachments/assets/da8adb8c-6301-4b85-a277-7390ae943d82)


