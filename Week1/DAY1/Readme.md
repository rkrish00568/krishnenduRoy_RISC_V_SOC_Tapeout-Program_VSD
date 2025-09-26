# 📘 Day 1: Introduction to Verilog RTL Design & Synthesis

Welcome to **Day 1** of the RTL Workshop!  
Today, you'll embark on your journey into **digital design** by learning Verilog, open-source simulation with **Icarus Verilog (iverilog)**, and the basics of logic synthesis using **Yosys**.  

This guide will walk you through **essential concepts** and **practical labs** to build a strong foundation in RTL design.

---

## 📑 Table of Contents
1. [What is a Simulator, Design, and Testbench?](#1-what-is-a-simulator-design-and-testbench)  
2. [Getting Started with iverilog](#2-getting-started-with-iverilog)  
3. [Lab: Simulating a 2-to-1 Multiplexer](#3-lab-simulating-a-2-to-1-multiplexer)  
4. [Verilog Code Analysis](#4-verilog-code-analysis)  
5. [Introduction to Yosys & Gate Libraries](#5-introduction-to-yosys--gate-libraries)  
6. [Synthesis Lab with Yosys](#6-synthesis-lab-with-yosys)  
7. [Summary](#7-summary)  

---

## 1. What is a Simulator, Design, and Testbench?

### 🖥️ Simulator
A **simulator** checks your digital circuit’s behavior by applying test inputs and observing outputs.  
This ensures correctness before hardware implementation.

### 📐 Design
The **design** is your Verilog RTL code that describes the intended logic.

### 🧪 Testbench
A **testbench** is a simulation environment that feeds inputs into the design and verifies outputs.

<div align="center">
  <img src="https://github.com/user-attachments/assets/93927b96-df80-4da5-b801-284fc2cc6757" alt="Design & Testbench Overview" width="70%">
</div>

---

## 2. Getting Started with iverilog

**iverilog** is an open-source simulator for Verilog.  

### Simulation Flow:
<div align="center">
  <img src="https://github.com/user-attachments/assets/3ca190fb-cfa4-4abb-b9e1-0151b3c4bdba" alt="iverilog Simulation Flow" width="70%">
</div>

- Provide both **design** and **testbench** to iverilog.  
- The simulator generates a `.vcd` file, viewable in **GTKWave**.  

---

## 3. Lab: Simulating a 2-to-1 Multiplexer

Let’s simulate a **2-to-1 multiplexer**!

### 🔹 Step 1: Clone the Workshop Repository
```bash
git clone https://github.com/kunalg123/sky130RTLDesignAndSynthesisWorkshop.git
cd sky130RTLDesignAndSynthesisWorkshop/verilog_files
