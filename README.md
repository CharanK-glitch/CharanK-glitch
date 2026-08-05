<div align="center">
  <!-- Dynamic Typing Effect -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=Hardware+%26+Microarchitecture+Security;Side-Channel+Analysis+%26+PQC;RTL-to-GDSII+%26+RISC-V+Architectures" alt="Typing SVG" />
  </a>

  <br><br>

  <p align="center">
    <b>Project Associate @ Cystar Lab, IIT Madras</b><br>
    <i>Hardware Security Researcher (IIT Kharagpur | AMD)</i>
  </p>

  <div align="center">
    <a href="mailto:kashmahanticharan@gmail.com"><img src="https://img.shields.io/badge/Email-kashmahanticharan%40gmail.com-blue?style=flat-square&logo=gmail"></a>
  </div>
</div>

<br>

## 👨‍💻 About My Work

I specialize in securing hardware at the foundational level, from microarchitectural leakage to post-quantum cryptography. My research spans academic labs at IIT Madras and IIT Kharagpur, alongside industry experience optimizing and validating systems at AMD. 

- 🔭 **Currently focusing on:** Micro-architectural Leakage Prevention, GPU performance optimization, and CPU-GPU co-design.
- ⚡ **Core domains:** Side-Channel Analysis, Fault Injection, ASIC/FPGA Design, and RISC-V Architectures.
- 🛠️ **Building:** Custom Verilog-based GPU accelerators and validating them on AWS FPGAs.

<br>

## ⚙️ Tech Stack & Tools

<p align="center">
  <!-- Uses Skillicons for a very clean, uniform look -->
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=cpp,python,linux,aws,github,vscode&theme=dark" />
  </a>
</p>
<p align="center">
  <i>C++ • Python • Verilog • Chisel • Linux • AWS FPGAs</i>
</p>

<br>

## 🧠 Research & Repository Architecture

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
