# Half Adder in Verilog

## 📌 Overview

This project implements a **Half Adder** using Verilog HDL. A half adder adds two single-bit binary numbers and produces:

* **Sum (S)**
* **Carry (C)**

## ⚙️ Logic

* Sum = A ⊕ B (XOR)
* Carry = A ⋅ B (AND)

## 📊 Truth Table

| A | B | Sum | Carry |
| - | - | --- | ----- |
| 0 | 0 | 0   | 0     |
| 0 | 1 | 1   | 0     |
| 1 | 0 | 1   | 0     |
| 1 | 1 | 0   | 1     |

## 📂 Files

* `half_adder.v` → Main Verilog module
* `half_adder_tb.v` → Testbench for simulation

## ▶️ Simulation

You can simulate using tools like:

* ModelSim
* Vivado
* Icarus Verilog

### Example (Icarus Verilog)

```bash
iverilog -o half_adder half_adder.v half_adder_tb.v
vvp half_adder
```

## 📸 Output Example

```
A B | Sum Carry
0 0 |  0    0
0 1 |  1    0
1 0 |  1    0
1 1 |  0    1
```

## 🚀 Author

thasmia
