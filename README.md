# VHDL-Based-EduCPU
A VHDL/Java-based Computer Organization and Design project demonstrating processor architecture concepts, instruction execution, and system-level design. Includes source code, documentation, and simulation files.


## 📖 Project Overview
The project is structured to showcase important phases of computer organization:

1. **Instruction Set Simulation**  
   - Implements a simplified instruction set architecture (ISA).  
   - Demonstrates fetching, decoding, and executing instructions.  

2. **Control Unit Design**  
   - Models control flow for arithmetic, logical, and memory operations.  
   - Highlights the separation between datapath and control.  

3. **Processor Organization**  
   - Explores registers, ALU operations, memory interactions, and I/O.  
   - Provides an educational foundation for understanding CPU internals.  

---

## 🛠️ Technologies Used
- **Java** (primary implementation language)  
- **Simulation models** for instruction processing  
- Standard I/O for testing and validation  

---

## 📂 Repository Structure
```

.
├── src/                  # Source code files
├── docs/                 # Documentation and design notes
├── tests/                # Test cases and simulation runs
├── outputs/              # Sample execution outputs
└── README.md             # Project documentation

````

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/COdesign.git
cd COdesign
````

### 2. Compile the project

```bash
javac src/*.java
```

### 3. Run the project

```bash
java src/Main
```

---

## ✅ Example

Sample input (assembly-like instructions):

```text
LOAD R1, 5
ADD R1, R2
STORE R1, 100
```

Sample output:

```text
R1 <- 5
R1 <- R1 + R2
Memory[100] <- R1
```

---

## 📌 Future Enhancements

* Extend the instruction set with more operations.
* Add pipelining simulation.
* Implement cache and memory hierarchy modeling.
* Provide a GUI visualization of processor execution.


## 📜 License


This project is licensed under the Creative Commons Attribution-NoDerivatives 4.0 International License. You are free to share the work, but you cannot modify it or create derivatives. Proper attribution must be given to the original author.
You can view the full license text here: [CC BY-ND 4.0 License](https://creativecommons.org/licenses/by-nd/4.0/legalcode)
![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC%20BY%20ND%204.0-lightgrey)


