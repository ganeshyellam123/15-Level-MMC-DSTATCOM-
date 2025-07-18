# Power Quality Improvement in the Distribution Grid using 15-Level MMC-Based DSTATCOM

This project presents a novel approach to enhance power quality and regulate power factor in distribution networks using a 15-level Modular Multilevel Converter (MMC) integrated with DSTATCOM capabilities.

## 🔍 Objective

- Improve voltage stability and reduce harmonics in distribution grids.
- Eliminate the need for external capacitor banks or separate FACTS devices.
- Utilize MATLAB/Simulink to simulate a wind-energy-driven, power-quality-improving inverter system.

## ⚙️ System Highlights

- **Topology Used**: Modular Multilevel Converter (MMC)
- **Control Technique**: Power angle (δ) for active power and modulation index (m) for reactive power.
- **Applications**: Wind energy systems, rural grid stabilization, FACTS-based compensation.

## 📁 Project Structure

| Folder | Description |
|--------|-------------|
| `/report` | Contains the original project report PDF |
| `/simulink_models` | MATLAB Simulink `.slx` files of 15-level MMC with DSTATCOM |
| `/images` | Diagrams and waveforms used in the project |
| `/data` | Simulation outputs (MATLAB `.mat` files) |
| `/docs` | Technical documentation and presentation materials |
| `/references` | Research citations in `.bib` format |

## 📊 Simulation Environment

- **Software**: MATLAB R2021b or later
- **Toolboxes Required**:
  - Simulink
  - Simscape Power Systems
  - Control Systems Toolbox

## 🧪 Key Results

- **THD Improvements** across levels:
  - 5-level: ~14%
  - 7-level: ~9.8%
  - 11-level: ~5.7%
  - 15-level: ~3.1%

- **Output Waveforms**: Closer to sinusoidal as the number of levels increases
- **PF Correction**: Stable at ~0.99 using the integrated control strategy

## 📝 Authors

- Y. Ganesh (19F21A0210)
- Shaik Afreen (19F21A0201)
- S. Lakshmi Narayana (19F21A0250)
- N. Ramu, G. Rajesh, Shaik Subhan

## 📚 References

See `/references/cited_papers.bib` for all technical papers and standards referenced.

## 🛡️ License

This project is licensed under the MIT License. See `LICENSE` file for more details.

## 📬 Contact

For queries or contributions, please contact the authors or raise an issue.

