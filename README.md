# Hi there, I'm Moonis Amir Zaman 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/moonis-amir-zaman-841112253/)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0007-2172-2765)
[![IEEE TCAS-II Paper](https://img.shields.io/badge/IEEE%20TCAS--II-Published%20Author-blue)](https://doi.org/10.1109/TCSII.2025.3633181)
[![Email](https://img.shields.io/badge/Email-moonisamir10%40gmail.com-red)](mailto:moonisamir10@gmail.com)

🎓 **M.Sc. Student in Microelectronics & Chip Design** at **Technical University of Munich (TUM)**  
💼 **Working Student** at **Infineon Technologies AG** (Munich) — RISC-V Decoder & Logic Synthesis (Cadence Genus / MetaRTL)  
🏆 **Rector's Gold Medalist** for Best B.Sc. Engineering Thesis (NUST)  
📍 **Munich, Germany**

---

### 🔬 Technical Competencies

* **Digital Design & RTL**: SystemVerilog, Verilog, VHDL, MetaRTL, RISC-V (RV32I/IMC), Pipeline Architecture, Cache Design.
* **Verification (DV)**: UVM 1.2, SystemVerilog Assertions (SVA), Constrained-Random Testing, Functional & Code Coverage, cocotb, Verilator, QuestaSim, Xcelium, VCS.
* **Design for Test (DFT) & ATPG**: IEEE 1149.1 JTAG TAP, IEEE 1500 Core Wrapper, March-C/Checkerboard MBIST, Glitch-Free OCC & At-Speed LOC, Multi-Chain Scan Stitching, `2:8`/`8:2` LFSR+XOR Compression & X-Masked MISR, Stuck-At ATPG (`Atalanta`, `AUCOHL Fault`), ATE Fail Diagnosis.
* **EDA Tools & ASIC Flow**: Cadence Genus, Synopsys Fusion Compiler, PrimeTime (STA), Conformal LEC, SpyGlass (Lint/CDC), Yosys, OpenSTA, `IHP SG13G2` 130nm PDK.
* **FPGA Prototyping**: AMD/Xilinx Vivado (Artix-7, Virtex-7, Zynq UltraScale+), Intel Quartus (DE10).
* **Scripting & Automation**: Python, Tcl, Bash/Linux, Make, C/C++, Git.

---

### 🚀 Featured Hardware Projects

| Project | Highlights | Tools / Technologies |
|:---|:---|:---|
| **[RISC-V SoC DFT, Verification & ASIC Signoff](https://github.com/MoonisAmir10/Classical-5-stage-pipelined-RISCV-Processor-In-Verilog/tree/main/DFT-ASIC-Verification)** | End-to-end open-source DFT, DV, ATPG & 9-corner OpenSTA/SDF signoff on RV32I + 2-way cache (`IHP SG13G2` 130nm: `169.49 MHz` typ / `110.50 MHz` slow, `0.2982 mm²` stdcell = `41,086 GE`, `19.28 mW` @ `100 MHz`). JTAG, IEEE 1500, March-C MBIST, OCC, 8-ch scan (`99.983%` SA FC, `8.70x` Hybrid compression), SVA/cocotb DV & ATE debug. | SystemVerilog, SVA, Verilator, cocotb, Yosys, `IHP SG13G2`, Fault/Atalanta, OpenSTA |
| **[UVM Register File Verification](https://github.com/MoonisAmir10/uvm-register-file-verification)** | Enterprise UVM 1.2 testbench with Register Abstraction Layer (RAL), front-door/back-door verification, 100% statement coverage. | SystemVerilog, UVM 1.2, QuestaSim |
| **[Classical 5-Stage RISC-V Processor](https://github.com/MoonisAmir10/Classical-5-stage-pipelined-RISCV-Processor-In-Verilog)** | 32-bit single-core RV32I pipelined CPU with hazard detection, data forwarding, and 2-way set-associative cache (`168.07 MHz`, `534` LUTs, `625` FFs), extended with full ASIC DFT flow. | Verilog, Artix-7 FPGA, Vivado, `IHP SG13G2` |
| **Hardware-Efficient NTT Accelerator** *(IEEE TCAS-II)* | Novel Twiddle Factor Generator and DSP-efficient multipliers for FHE acceleration. $2.7\times$ ATP improvement. | Verilog, Xilinx Vivado, TCAS-II |
| **Secure Sensor-to-MCU AEAD Accelerator** | ASCON-128 cryptographic engine with 3840-bit SRAM PUF hardware root of trust and fuzzy extractor. | GF 22nm, Fusion Compiler |

---

### 📄 Publications
* **Moonis Amir Zaman**, M. B. Khan, W. Ahmad, A. Khalid, and M. O’Neill, *"A Lightweight and Hardware-Efficient NTT FPGA Accelerator for FHE Applications,"* **IEEE Transactions on Circuits and Systems II: Express Briefs (TCAS-II)**, 2025. [DOI: 10.1109/TCSII.2025.3633181](https://doi.org/10.1109/TCSII.2025.3633181).
