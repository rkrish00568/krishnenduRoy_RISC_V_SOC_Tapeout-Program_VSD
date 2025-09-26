# 🖥️ Workshop Day One  
**Topic:** Introduction to Verilog RTL Design & Synthesis  

Welcome to **Day One** of the workshop!  
This session introduces you to **Verilog RTL design, simulation, and synthesis**.  

---

## 📌 Agenda
1. What is a **Simulator**, **Design**, and **Testbench**?  
2. **Lab Session:** Simulate a Multiplexer using Verilog.  
3. Introduction to **Yosys** and **Gate Libraries**.  
4. **Lab Session:** RTL-to-Gates Synthesis with Yosys.  

---

## 1️⃣ What is a Simulator, Design, and Testbench?
- **Design** → RTL (Register Transfer Level) description written in Verilog.  
- **Simulator** → Software tool that checks the design behavior before fabrication.  
- **Testbench** → Stimulus code written in Verilog to test the design.  

---

## 2️⃣ Lab: Simulate a Multiplexer using Verilog
**Example: 2:1 Multiplexer**

```verilog
module mux2to1 (
  input wire a, b, sel,
  output wire y
);
  assign y = sel ? b : a;
endmodule
