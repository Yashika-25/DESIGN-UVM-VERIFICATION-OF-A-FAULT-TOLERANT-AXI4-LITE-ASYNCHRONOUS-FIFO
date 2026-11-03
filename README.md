🚀 **Design & UVM Verification of a Fault-Tolerant AXI4-Lite Asynchronous FIFO**

A fault-tolerant AXI4-Lite asynchronous FIFO designed in SystemVerilog to enable reliable data transfer between different clock domains. The design incorporates SECDED (Single Error Correction, Double Error Detection) ECC for data integrity and is verified using a UVM-based verification environment.

📖 **Project Overview:**

Clock Domain Crossing (CDC) is one of the most critical challenges in modern digital systems. This project implements an AXI4-Lite compatible asynchronous FIFO capable of safely transferring data between independent clock domains while detecting and correcting transmission errors.

The design combines:

✅ AXI4-Lite Interface

✅ Asynchronous FIFO Architecture

✅ Gray Code Pointer Synchronization

✅ Two-Flip-Flop Synchronizers

✅ SECDED ECC Protection

✅ UVM-Based Functional Verification

✨ **Key Features**

*  Asynchronous FIFO
Independent read and write clock domains
Reliable cross-clock data transfer
Full and Empty flag generation

*  Fault Tolerance
SECDED ECC implementation
Single-bit error correction
Double-bit error detection
Improved data reliability

*  Clock Domain Crossing (CDC)
Gray-code read/write pointers
Two-stage synchronizers
Reduced metastability risk

*  UVM Verification
Constrained-random testing
Functional coverage collection
Scoreboard-based checking
Assertion-based verification

🔍 **Verification Methodology**

The design was verified using a complete UVM testbench consisting of:

* Driver

* Monitor

* Sequencer

* Agent

* Scoreboard

* Coverage Collector

* Assertions

Test scenarios include:

✅ Read Transactions

✅ Write Transactions

✅ Simultaneous Read/Write Operations

✅ FIFO Full Condition

✅ FIFO Empty Condition

✅ ECC Error Injection

✅ Error Detection & Correction Validation

📂 Repository Structure

├── **rtl/**           # RTL design files

├── **uvm/**          # UVM verification components

├── **assertions/**     # SystemVerilog assertions

├── **tb/**             # Top-level testbench

├── **sim/**            # Compilation and simulation files

├── **docs/**          # Project documentation

└── **images/**         # Architecture and waveform screenshots


🛠️ **Tools & Technologies**

* SystemVerilog

* UVM (Universal Verification Methodology)

* Synopsys VCS

* Synopsys Verdi

🎯 **Learning Outcomes**

Through this project, the following concepts were explored:

* AXI4-Lite Protocol

* Asynchronous FIFO Design

* Clock Domain Crossing (CDC)

* Error Correction Coding (ECC)

* UVM Verification

* Functional Coverage Analysis

* Assertion-Based Verification

👨‍💻 **Authors**

1. Yashika Tyagi

 2. Dev Gogia
