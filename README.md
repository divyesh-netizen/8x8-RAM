# 8x8 RAM in Verilog

This project demonstrates the design and working of a simple **8x8 RAM (Random Access Memory)**.

## 📌 Overview

* Memory size: **8 locations**
* Each location stores: **8-bit data**
* Total memory capacity: **64 bits**

## ⚙️ Inputs & Outputs

| Signal | Description                                |
| ------ | ------------------------------------------ |
| `clk`  | Clock signal                               |
| `we`   | Write Enable (1 = write, 0 = read)         |
| `addr` | 3-bit address (selects one of 8 locations) |
| `din`  | 8-bit input data                           |
| `dout` | 8-bit output data                          |

## 🔁 Working

### Write Operation

* When write enable is active, data is stored in the selected memory location.
* The operation occurs on the clock edge.

### Read Operation

* When write enable is inactive, data from the selected memory location is sent to the output.

## 🎯 Key Concepts

* Synchronous memory design
* Address-based data access
* Controlled read and write operations
* Basic digital memory architecture

## 🚀 Applications

* Learning digital design concepts
* Practice for Verilog and VLSI
* Foundation for building larger memory modules

## 🧪 Future Improvements

* Add simulation and waveform analysis
* Increase memory size (e.g., 16x8, 32x8)
* Implement advanced memory structures like register files

---

⭐ A simple and beginner-friendly project to understand memory design in Verilog
# 8x8-RAM
