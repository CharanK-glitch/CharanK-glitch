<div align="center">

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=Hardware+%26+Microarchitecture+Security;Side-Channel+Analysis+%26+PQC;RTL-to-GDSII+%26+RISC-V+Architectures" alt="Typing SVG" />
</h1>

<p align="center">
  <b>Project Associate @ Cystar Lab, IIT Madras</b> | <i>PhD Student @ SEAL Lab, IIT Kharagpur</i><br>
  <i>Former Student Research Intern @ Advanced Micro Devices (AMD), Austin, TX</i>
</p>

<p align="center">
  <a href="mailto:kashmahanticharan@gmail.com"><img src="https://img.shields.io/badge/Email-kashmahanticharan%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://scholar.google.com/"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white" alt="Google Scholar"/></a>
  <a href="https://github.com/"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

</div>

---

### 💫 About Me

I am a hardware security researcher focused on the intersection of computer architecture, applied cryptography, and microarchitectural security. From investigating side-channel vulnerabilities and fault injections to designing custom Verilog-based GPU accelerators, I am driven by the challenge of securing next-generation computing systems from the ground up.

* 🔬 **Research Focus:** Microarchitectural Leakage, Hardware Security, Post-Quantum Cryptography (PQC), CPU-GPU Co-Design Synchronization, and VLSI.
* 🎓 **Academic & Professional Journey:** Advancing research at IIT Madras and IIT Kharagpur, building upon industry insights gained during my time at AMD. I am also an alumnus of the ACM India Summer School on Foundations of Hardware Security.
* 💬 **Ask Me About:** Side-Channel Attacks, Fault Injection, RISC-V Cores, ASIC Design, FPGA Validation, & Verilog.
* ⚡ **Fun Fact:** When I'm not designing secure silicon or grinding algorithms on LeetCode, I'm probably catching up on the latest NBA games.

---

### 🛠️ Technical Arsenal

**Languages & Frameworks**
<p>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Verilog-1E8CBE?style=for-the-badge&logo=verilog&logoColor=white" />
  <img src="https://img.shields.io/badge/Chisel-000000?style=for-the-badge&logo=scala&logoColor=white" />
</p>

**Hardware & Architecture**
<p>
  <img src="https://img.shields.io/badge/RISC--V-000000?style=for-the-badge&logo=riscv&logoColor=white" />
  <img src="https://img.shields.io/badge/FPGA-00599C?style=for-the-badge&logo=intel&logoColor=white" />
  <img src="https://img.shields.io/badge/ASIC_Design-4B0082?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Post--Quantum_Cryptography-2E8B57?style=for-the-badge" />
</p>

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
