<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=Hardware+%26+Microarchitecture+Security;Side-Channel+Analysis+%26+PQC;RTL-to-GDSII+%26+RISC-V+Architectures" alt="Typing SVG" />
</h1>

<p align="center">
  <b>Project Associate @ Cystar Lab, IIT Madras</b> | <i>Hardware Security Researcher</i>
</p>

---

### 💫 About Me
* 🔬 **Research Focus:** Hardware Security, Post-Quantum Cryptography (PQC), & Microarchitectural Leakage
* 💬 **Ask Me About:** Side-Channel Attacks, Fault Injection, RISC-V Cores, & ASIC/FPGA Design
* 📫 **Contact:** [kashmahanticharan@gmail.com](mailto:kashmahanticharan@gmail.com)

---

### 🧠 Research & Repository Architecture

```mermaid
graph TD
    %% Node Styling
    classDef root fill:#0D1117,stroke:#38BDF8,stroke-width:2px,color:#fff;
    classDef core fill:#161B22,stroke:#58A6FF,stroke-width:1px,color:#38BDF8;
    classDef repo fill:#21262D,stroke:#3FB950,stroke-width:1.5px,color:#fff;
    classDef stack fill:#161B22,stroke:#8B949E,stroke-width:1px,color:#8B949E;

    %% Root
    Me("⚡ Charan Kasimahanti<br/><i>Hardware Security Research</i>"):::root

    %% Domains
    Me --> Architecture["💻 Microarchitecture & Hardware Security"]:::core
    Me --> Crypto["🔐 Side-Channel Analysis & PQC"]:::core

    %% Repositories
    Architecture --> RV32I["🛠️ RV32I<br/><i>Sapphire SoC / RISC-V FPGA Core</i>"]:::repo
    Crypto --> PoMMES["🛡️ PoMMES<br/><i>Micro-architectural Leakage Prevention</i>"]:::repo

    %% Tech Connections
    RV32I --- Verilog["Verilog / Chisel"]:::stack
    RV32I --- FPGA["FPGA / AXI4"]:::stack
    PoMMES --- Cpp["C++ / C"]:::stack
    PoMMES --- Cryptography["Masked Software"]:::stack
