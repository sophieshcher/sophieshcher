<div align="center">

# Sofiia Shcherbyna (Софія Щербина)
### Applied Physics • Scientific Computing • Embedded Systems & PCB Design

[![Email](https://img.shields.io/badge/Gmail-s0.shcherbyna%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:s0.shcherbyna@gmail.com)
[![Academic Email](https://img.shields.io/badge/KPI-shcherbyna.sofiia__ff41%40edu.kpi.ua-0057B7?style=for-the-badge&logo=academia&logoColor=white)](mailto:shcherbyna.sofiia_ff41@edu.kpi.ua)
[![Portfolio Repo](https://img.shields.io/badge/Main_Portfolio-sophieshcher%2Fprojects-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sophieshcher/projects)

</div>

---

## About Me

Physics & Engineering student at **Igor Sikorsky Kyiv Polytechnic Institute (KPI, Institute of Physics and Technology / ФТІ)** focused on:
- **Scientific Computing & Numerical Methods:** High-performance simulations in **C++ (OpenMP)**, **Python**, and **MATLAB** (astrophysical N-body dynamics, heat transfer, RLC circuits, signal processing).
- **Embedded Hardware & PCB Design:** Microcontroller firmware (**STM32**, **Arduino/ATmega328P**), motor control electronics, schematics & multi-layer PCB layout in **Altium Designer**, and 3D CAD modeling in **AutoCAD**.
- **Web & Interactive Visualization:** Modern Front-End interfaces (**React**, **JavaScript ES6+**, **HTML5/CSS3**).

### Tech Stack & Engineering Tools

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![OpenMP](https://img.shields.io/badge/OpenMP-Parallel_Computing-blue?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-Simulink_%26_Live_Scripts-E16737?style=flat-square)
![STM32](https://img.shields.io/badge/STM32-Embedded_C-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-ATmega328P-00979D?style=flat-square&logo=arduino&logoColor=white)
![Altium Designer](https://img.shields.io/badge/Altium_Designer-PCB_%26_Gerber-A5915F?style=flat-square&logo=altiumdesigner&logoColor=white)
![AutoCAD](https://img.shields.io/badge/AutoCAD-3D_CAD-E51050?style=flat-square&logo=autodesk&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

## Featured Engineering & Scientific Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>1. <a href="https://github.com/sophieshcher/cms-dimuon-invariant-mass">CERN CMS Dimuon Invariant Mass (Z → μ⁺μ⁻)</a></h3>
      <p>High-energy particle physics analysis of real <b>CERN CMS Open Data</b> collision events in <b>C++ (CERN ROOT)</b>. Reconstructs the 4-momentum invariant mass spectrum of opposite-sign muon pairs and extracts the <b>Z⁰ boson</b> pole mass (<code>91.12 ± 0.08 GeV/c²</code>) via a relativistic Breit–Wigner + continuum background fit.</p>
      <p>
        <a href="https://github.com/sophieshcher/cms-dimuon-invariant-mass"><b>Standalone Repo</b></a> •
        <a href="https://github.com/sophieshcher/projects/tree/main/cms-dimuon-invariant-mass"><b>In Portfolio</b></a> •
        <a href="https://github.com/sophieshcher/cms-dimuon-invariant-mass/blob/main/src/analyze_dimuon.cpp"><b>ROOT C++ Code</b></a> •
        <a href="https://github.com/sophieshcher/cms-dimuon-invariant-mass/blob/main/results/z_boson_fit.png"><b>Z-Peak Fit Plot</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>2. <a href="https://github.com/sophieshcher/projects/tree/main/N-body%20Gravitational%20Simulation">2D N-Body Gravitational Simulation</a></h3>
      <p>High-performance C++ astrophysical simulator comparing direct summation <code>O(N²)</code>, multi-threaded <b>OpenMP</b> parallelism, and the hierarchical <b>Barnes-Hut Quadtree</b> <code>O(N log N)</code> algorithm with Symplectic Leapfrog integration (up to <b>78.8× speedup</b> at N = 50,000).</p>
      <p>
        <a href="https://github.com/sophieshcher/projects/blob/main/N-body%20Gravitational%20Simulation/README.md"><b>Documentation & Benchmarks</b></a> •
        <a href="https://github.com/sophieshcher/projects/blob/main/N-body%20Gravitational%20Simulation/nbody_barneshut.cpp"><b>Barnes-Hut C++</b></a> •
        <a href="https://github.com/sophieshcher/projects/tree/main/N-body%20Gravitational%20Simulation/matlab_scripts"><b>MATLAB Scripts</b></a> •
        <a href="https://github.com/sophieshcher/projects/tree/main/N-body%20Gravitational%20Simulation/plots"><b>Plots</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>3. <a href="https://github.com/sophieshcher/projects/tree/main/proj-module-for-dc-motor">Smart Closed-Loop DC Motor Controller</a></h3>
      <p>Industrial/robotics actuator control module (<b>EPS 2026 Case 1.1.3</b>) built around <b>STM32F103C8</b>, <b>DRV8874</b> H-bridge driver with current sensing, <b>AS5600</b> 12-bit contactless magnetic encoder, and <b>TPS54302</b> buck converter with custom CRC-8 UART telemetry.</p>
      <p>
        <a href="https://github.com/sophieshcher/projects/blob/main/proj-module-for-dc-motor/README.md"><b>System Architecture</b></a> •
        <a href="https://github.com/sophieshcher/projects/tree/main/proj-module-for-dc-motor/Gerber"><b>Gerber & Schematics</b></a> •
        <a href="https://github.com/sophieshcher/projects/tree/main/proj-module-for-dc-motor/3D%20model"><b>3D CAD Model</b></a> •
        <a href="https://github.com/sophieshcher/projects/blob/main/proj-module-for-dc-motor/%D0%9A%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%B0_1.1.3_%D0%A0%D0%BE%D0%B7%D1%80%D0%BE%D0%B1%D0%BA%D0%B0%20%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D1%8F%20%D0%BA%D0%B5%D1%80%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F%20DC-%D0%BC%D0%BE%D1%82%D0%BE%D1%80%D0%BE%D0%BC.pptx.pdf"><b>Presentation</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>4. <a href="https://github.com/sophieshcher/projects/tree/main/Decimal-to-Binary%20Decoder">Decimal-to-Binary Hardware Trainer</a> & <a href="https://github.com/sophieshcher/projects/tree/main/matlab">MATLAB</a></h3>
      <p>Pocket embedded trainer based on <b>ATmega328P (Arduino)</b> and <b>HD44780 16×2 LCD</b>, plus interactive <b>MATLAB Live Scripts</b> for RLC circuit transient analysis and signal processing.</p>
      <p>
        <a href="https://github.com/sophieshcher/projects/blob/main/Decimal-to-Binary%20Decoder/README.md"><b>Arduino Trainer</b></a> •
        <a href="https://github.com/sophieshcher/projects/blob/main/Decimal-to-Binary%20Decoder/decimal-to-binary.pdf"><b>Schematic</b></a> •
        <a href="https://github.com/sophieshcher/projects/blob/main/matlab/proj_rlc_loop.mlx"><b>RLC Loop (.mlx)</b></a> •
        <a href="https://github.com/sophieshcher/projects/blob/main/matlab/proj_signal.mlx"><b>Signal Analysis</b></a>
      </p>
    </td>
  </tr>
</table>

---

## Quick Navigation: Project Parts & Submodules

### A. Scientific Computing, Numerical Methods & Programming ([`sophieshcher/projects`](https://github.com/sophieshcher/projects) & [`sophieshcher/cpp3`](https://github.com/sophieshcher/cpp3))

| Category / Module | Direct Links to Project Parts & Code | Technologies |
| :--- | :--- | :--- |
| **N-Body Simulation** | [Overview](https://github.com/sophieshcher/projects/tree/main/N-body%20Gravitational%20Simulation) • [Sequential Solver](https://github.com/sophieshcher/projects/blob/main/N-body%20Gravitational%20Simulation/nbody_sequential.cpp) • [OpenMP Solver](https://github.com/sophieshcher/projects/blob/main/N-body%20Gravitational%20Simulation/nbody_openmp.cpp) • [Barnes-Hut Quadtree](https://github.com/sophieshcher/projects/blob/main/N-body%20Gravitational%20Simulation/nbody_barneshut.cpp) • [Benchmark Suite](https://github.com/sophieshcher/projects/blob/main/N-body%20Gravitational%20Simulation/benchmark.cpp) • [CSV Data](https://github.com/sophieshcher/projects/tree/main/N-body%20Gravitational%20Simulation/data) • [Plots & GIF](https://github.com/sophieshcher/projects/tree/main/N-body%20Gravitational%20Simulation/plots) | `C++` `OpenMP` `MATLAB` |
| **Computational Methods** | [Main Folder](https://github.com/sophieshcher/projects/tree/main/computational%20methods) • [Lab 1](https://github.com/sophieshcher/projects/tree/main/computational%20methods/laba_1) • [Lab 2](https://github.com/sophieshcher/projects/tree/main/computational%20methods/laba_2) • [Lab 3](https://github.com/sophieshcher/projects/tree/main/computational%20methods/laba_3) • [Lab 4](https://github.com/sophieshcher/projects/tree/main/computational%20methods/laba_4) • [Lab 5](https://github.com/sophieshcher/projects/tree/main/computational%20methods/laba_5) • [Lab 6](https://github.com/sophieshcher/projects/tree/main/computational%20methods/laba_6) | `C++` `Numerical Analysis` |
| **Python & Thermal Physics** | [Main Folder (`прога`)](https://github.com/sophieshcher/projects/tree/main/%D0%BF%D1%80%D0%BE%D0%B3%D0%B0) • [Thermal Simulation (`therma.py`)](https://github.com/sophieshcher/projects/blob/main/%D0%BF%D1%80%D0%BE%D0%B3%D0%B0/therma.py) • [Lab 1](https://github.com/sophieshcher/projects/blob/main/%D0%BF%D1%80%D0%BE%D0%B3%D0%B0/shcherbyna-lab-1.py) • [Lab 2](https://github.com/sophieshcher/projects/blob/main/%D0%BF%D1%80%D0%BE%D0%B3%D0%B0/shcherbyna-lab-2.py) • [Lab 3](https://github.com/sophieshcher/projects/blob/main/%D0%BF%D1%80%D0%BE%D0%B3%D0%B0/shcherbyna-lab-3.py) • [Lab 4](https://github.com/sophieshcher/projects/blob/main/%D0%BF%D1%80%D0%BE%D0%B3%D0%B0/shcherbyna-lab-4.py) • [Lab 5](https://github.com/sophieshcher/projects/blob/main/%D0%BF%D1%80%D0%BE%D0%B3%D0%B0/shcherbyna_lab_5.py) • [Lab 6](https://github.com/sophieshcher/projects/blob/main/%D0%BF%D1%80%D0%BE%D0%B3%D0%B0/shcherbyna-lab-6.py) • [Lab 7](https://github.com/sophieshcher/projects/blob/main/%D0%BF%D1%80%D0%BE%D0%B3%D0%B0/Shcherbyna-lab-7.py) • [Lab 8](https://github.com/sophieshcher/projects/blob/main/%D0%BF%D1%80%D0%BE%D0%B3%D0%B0/shcherbyna_lab-8.py) | `Python` `Algorithms` |
| **C++ Algorithms (`cpp3`)** | [Repository (`cpp3`)](https://github.com/sophieshcher/cpp3) • [Lab 0](https://github.com/sophieshcher/cpp3/tree/main/lab_0) • [Lab 1](https://github.com/sophieshcher/cpp3/tree/main/lab_1) • [Lab 2](https://github.com/sophieshcher/cpp3/tree/main/lab_2) • [Lab 3](https://github.com/sophieshcher/cpp3/tree/main/lab_3) • [Lab 3–5](https://github.com/sophieshcher/cpp3/tree/main/lab_3-5) • [Lab 4](https://github.com/sophieshcher/cpp3/tree/main/lab_4) • [Lab 5](https://github.com/sophieshcher/cpp3/tree/main/lab_5) • [Lab 6](https://github.com/sophieshcher/cpp3/tree/main/lab_6) • [Lab 7](https://github.com/sophieshcher/cpp3/tree/main/lab_7) | `C++` `STL` `Data Structures` |

---

### B. Hardware, CAD, Electromagnetism & Optics ([`sophieshcher/projects`](https://github.com/sophieshcher/projects))

| Category / Module | Direct Links to Project Parts & Files | Domain |
| :--- | :--- | :--- |
| **DC Motor Control Module** | [Module Overview](https://github.com/sophieshcher/projects/tree/main/proj-module-for-dc-motor) • [Electrical Drawings (PDF)](https://github.com/sophieshcher/projects/blob/main/proj-module-for-dc-motor/Gerber/1.1.3%20module%20for%20DC%20motor%20electrical%20drawings.pdf) • [PCB Layout (PDF)](https://github.com/sophieshcher/projects/blob/main/proj-module-for-dc-motor/Gerber/PCB_Project%20(2).pdf) • [3D CAD Archive](https://github.com/sophieshcher/projects/tree/main/proj-module-for-dc-motor/3D%20model) • [Component Datasheets](https://github.com/sophieshcher/projects/tree/main/proj-module-for-dc-motor/datasheet%20components) | `STM32` `Altium` `PCB` |
| **AutoCAD 3D & Drawings** | [Main Folder (`autocad-model`)](https://github.com/sophieshcher/projects/tree/main/autocad-model) • [Final 3D Layout](https://github.com/sophieshcher/projects/blob/main/autocad-model/3dmodel-Layout3finananananleeee.pdf) • [Views & Sections](https://github.com/sophieshcher/projects/blob/main/autocad-model/%D0%B2%D0%B8%D0%B4%D0%B8%20%D1%96%20%D1%80%D0%BE%D0%B7%D1%80%D1%96%D0%B7%D0%B8-Layout3.pdf) • [Parametrization](https://github.com/sophieshcher/projects/blob/main/autocad-model/%D0%B0%D1%80%D0%B0%D0%BC%D0%B5%D1%82%D1%80%D0%B8%D0%B7%D0%B0%D1%86%D1%96%D1%8F-Layout1.pdf) • [Array Modeling](https://github.com/sophieshcher/projects/blob/main/autocad-model/Massiveeekehgfdwsuydjeglfvwuehlrgid-Layout3.pdf) | `AutoCAD` `Engineering Graphics` |
| **Electromagnetism Labs** | [Main Folder (`elmag`)](https://github.com/sophieshcher/projects/tree/main/elmag) • [Lab 1](https://github.com/sophieshcher/projects/blob/main/elmag/untitled-1lab.pdf) • [Lab 3](https://github.com/sophieshcher/projects/blob/main/elmag/laba3.pdf) • [Lab 4](https://github.com/sophieshcher/projects/blob/main/elmag/laba4.pdf) • [Lab 5](https://github.com/sophieshcher/projects/blob/main/elmag/EM_Lab5.pdf) • [Labs 6–7](https://github.com/sophieshcher/projects/blob/main/elmag/laba6_7.pdf) • [Lab 8](https://github.com/sophieshcher/projects/blob/main/elmag/laba8.pdf) | `Electrodynamics` |
| **Optics Labs** | [Main Folder (`optics_lab`)](https://github.com/sophieshcher/projects/tree/main/optics_lab) • [Lab 1](https://github.com/sophieshcher/projects/blob/main/optics_lab/opt_lab_1.pdf) • [Lab 3](https://github.com/sophieshcher/projects/blob/main/optics_lab/opt_lab_3.pdf) • [Lab 4](https://github.com/sophieshcher/projects/blob/main/optics_lab/opt_lab_4.pdf) • [Lab 6](https://github.com/sophieshcher/projects/blob/main/optics_lab/opt_laba_6.pdf) • [Lab 7](https://github.com/sophieshcher/projects/blob/main/optics_lab/opt-laba7.pdf) • [Lab 8](https://github.com/sophieshcher/projects/blob/main/optics_lab/opt-lab8.pdf) | `Physical & Wave Optics` |

---

### C. Web Development & Front-End Projects

| Repository | Direct Links to Mini-Apps & Components | Stack |
| :--- | :--- | :--- |
| **[`goiteens-front-end`](https://github.com/sophieshcher/goiteens-front-end)** | [OpenWeather App](https://github.com/sophieshcher/goiteens-front-end/tree/main/open-weather) • [Cinema App](https://github.com/sophieshcher/goiteens-front-end/tree/main/Cinema) • [Tic-Tac-Toe](https://github.com/sophieshcher/goiteens-front-end/tree/main/Tic-tac-Toe) • [ToDo List](https://github.com/sophieshcher/goiteens-front-end/tree/main/ToDo%20list%20project%20copy) • [Calculator](https://github.com/sophieshcher/goiteens-front-end/tree/main/calculator) • [Modal & Slider](https://github.com/sophieshcher/goiteens-front-end/tree/main/modal_menu_slider) • [Cookies Project](https://github.com/sophieshcher/goiteens-front-end/tree/main/cookies-project) • [Text Animation](https://github.com/sophieshcher/goiteens-front-end/tree/main/text_animation) | `JavaScript` `HTML5` `CSS3` |
| **[`goit-react-hw-01-components`](https://github.com/sophieshcher/goit-react-hw-01-components)** | [Profile Component](https://github.com/sophieshcher/goit-react-hw-01-components/tree/main/homework-1/src/components/profile) • [Statistics](https://github.com/sophieshcher/goit-react-hw-01-components/tree/main/homework-1/src/components/statistics) • [FriendList](https://github.com/sophieshcher/goit-react-hw-01-components/tree/main/homework-1/src/components/friendList) • [TransactionHistory](https://github.com/sophieshcher/goit-react-hw-01-components/tree/main/homework-1/src/components/transactionHistory) | `React` `Components` |
| **Landing Pages & UI** | [`project_med`](https://github.com/sophieshcher/project_med) • [`Mastrelle-`](https://github.com/sophieshcher/Mastrelle-) • [`GameOfTeens_js`](https://github.com/sophieshcher/GameOfTeens_js) • [`NweItRep` (GameCards / NoWarInUkraine)](https://github.com/sophieshcher/NweItRep) | `HTML5` `CSS3` `JS` |

---

## Certificates & Engineering Competitions

- **[CodePlasma 2026 — Certificate (with translation)](https://github.com/sophieshcher/projects/blob/main/CodePlasma2026_Certificate_with_translation.pdf)** — Plasma Physics & Tokamak Modeling / Scientific Computing
- **[EPS 2026 (Engineering Project Sprint) — Certificate (with translation)](https://github.com/sophieshcher/projects/blob/main/EPS2026_Certificate_with_translation.pdf)** — Hardware & Embedded Systems Development (Smart DC Motor Control Module)
- **[PolyTECH EDU 2025 — Certificate (with translation)](https://github.com/sophieshcher/projects/blob/main/PolyTECH_EDU_2025_Certificate_with_translation.pdf)** — Engineering & Science Competition
