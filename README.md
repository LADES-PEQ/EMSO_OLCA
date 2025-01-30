# EMSO_OLCA
> The EMSO_OLCA tool was developed in C++ to integrate the life cycle analysis software OpenLCA with the Environment for Modeling, Simulation, and Optimization of Processes – EMSO.

Integrating life cycle analysis into the environment for process modeling and simulation is particularly interesting as it allows not only for online emissions monitoring but also for designing equipment based on bioeconomy principles, performing environmental techno-economic assessments of processes, and optimizing processes and control based on environmental metrics.

EMSO is an environment for modeling, simulation, and optimization of processes, free for academic use (SOARES and SECCHI, 2003). It is faster in simulation time compared to commercial simulators, making it suitable for real-time applications. It offers integration with OPC, Python, Matlab, Scilab / OPC / Excel and easy integration with real-time industrial systems (SOARES and SECCHI, 2003).

## 📖 Overview
This repository contains the source code for EMSO_OLCA, developed by Simone Miyoshi at the Laboratory of Software Development for Process Control and Optimization (LADES) - COPPE/UFRJ.

## 🚀 Features
- [OpenLCA Integration to EMSO]
- [Fast solving]
- [Flexibility]
- [OpenLCA database]

## 📦 Installation
To install and use this project, follow these steps:

### Prerequisites
Ensure you have the following dependencies installed:
-EMSO software installed
```

### Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/LADES-PEQ/EMSO_OLCA.git
   ```
2. EMSO installation:
   https://www.enq.ufrgs.br/alsoc/download/

3. OpenLCA Database, register in https://nexus.openlca.org/ and Download the database.

4. Please look for EMSO_OLCA Manual for .dll installation.
 

## 📂 Repository Structure
```
├── Documentation/         # Documentation and Manuals
├── EMSOSimulationFiles/   # Simulation files
├── MetodosData/           # Libraries
├── Results/               # Results
├── LICENSE                # License information
├── README.md              # Project documentation
├── EMSO_OLCA.dll          # DLL of EMSO_OLCA
```

## ✏️ Authors & Contributors
This project was developed by:

- **Simone Miyoshi** - [Post doctorate Researcher] - [smiyoshi@peq.coppe.ufrj.br]
- **[Argimiro Secchi]** - [Full Professor]

We welcome contributions!

## 🔬 References & Publications
If you use this work in your research, please cite the following publications:
- Miyoshi, S. C., & Secchi, A. R. (2024). Simultaneous Life Cycle Assessment and Process Simulation for Sustainable Process Design. Processes, 12(7), 1285. https://doi.org/10.3390/pr12071285


BibTeX:
```bibtex
@Article{ Miyoshi2024
AUTHOR = {Miyoshi, Simone C. and Secchi, Argimiro R.},
TITLE = {Simultaneous Life Cycle Assessment and Process Simulation for Sustainable Process Design},
JOURNAL = {Processes},
VOLUME = {12},
YEAR = {2024},
NUMBER = {7},
ARTICLE-NUMBER = {1285},
URL = {https://www.mdpi.com/2227-9717/12/7/1285},
ISSN = {2227-9717},
ABSTRACT = {While there are software tools available for helping to conduct life cycle assessment (LCA), such as OpenLCA, these tools lack integration with process design, simulation, and optimization software. As LCA has a critical role in sustainable product design, this paper presents a platform called EMSO_OLCA, which integrates the LCA provided by OpenLCA into the Environment for Modeling, Simulation, and Optimization (EMSO). EMSO_OLCA incorporates a database of environmental impact assessment methodologies from OpenLCA and aligns with the principles of LCA outlined in ISO 14040 and ISO 14044. Validation tests were conducted to compare the results obtained by the LCA of sugarcane ethanol using OpenLCA and EMSO_OLCA, revealing a high level of agreement. The average relative error was 0.045%, indicating a negligible discrepancy between the tools. Moreover, it took only 0.3 s for the calculation, which is desirable for use with process system engineering tools. A second case study was applied to combined steam and electricity production from the combustion of sugarcane bagasse and straw in a combined heat and power system. The results show the integration of LCA with simulation and sensitivity analysis tools, thus supporting sustainable decision-making processes. EMSO_OLCA bridges the gap between LCA and process engineering, enabling a holistic approach to the sustainability, design, and implementation of environmentally friendly solutions.},
DOI = {10.3390/pr12071285}
}
```

## 🛡 License
This work is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0) License**.  
You are free to:
- **Use, modify, and distribute** this code for any purpose.
- **Cite the following reference** when using this code:


See the full license details in the [LICENSE](LICENSE) file.

## 📞 Contact
For any inquiries, please contact **[Simone]** at **[smiyoshi@peq.coppe.ufrj.br]** or open an issue in this repository.

## ⭐ Acknowledgments
We acknowledge the support of Brazilian National Agency of Petroleum, Natural Gas and Biofuels (ANP) and FINEP for sponsoring the Program of Human Resources 4.1 Digital Technologies in the O&G Sector.

