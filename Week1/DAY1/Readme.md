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
Let’s simulate a simple **2-to-1 multiplexer** using **iverilog**!  

---

### 🔹 Step 1: Clone the Workshop Repository
```bash
git clone https://github.com/kunalg123/sky130RTLDesignAndSynthesisWorkshop.git
cd sky130RTLDesignAndSynthesisWorkshop/verilog_files

### 🔹 Step 2: Install Required Tools
