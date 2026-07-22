# Molecular-docking-of-Acetylcholine-with-Acetylcholinesterase
# 🧬 Molecular Docking of Acetylcholine with Human Acetylcholinesterase (PDB: 4BDT)

This project demonstrates molecular docking of Acetylcholine (ACh) with Human Acetylcholinesterase (AChE) using SwissDock. The objective was to estimate the binding affinity of acetylcholine within the enzyme's active site.

This was my first molecular docking project and served as an introduction to structure based drug discovery and computational biology.

---

# Project Overview

Acetylcholinesterase (AChE) is an enzyme responsible for hydrolyzing the neurotransmitter acetylcholine at cholinergic synapses. Understanding how acetylcholine interacts with AChE explains enzyme function and forms the basis for studying inhibitors.

I docked acetylcholine into the crystal structure of human acetylcholinesterase (PDB ID: 4BDT) and analyzed the predicted binding conformations.

---

# Tools and Resources

- SwissDock – Molecular docking
- RCSB Protein Data Bank (PDB) – Protein structure retrieval
- PDB ID: 4BDT
- Ligand: Acetylcholine (ACh)

---

# Methodology

1. Retrieved the 3D structure of human acetylcholinesterase (4BDT) from the Protein Data Bank.
2. Selected acetylcholine as the ligand.
3. Submitted the protein and ligand to SwissDock.
4. Used Prankweb to predict coordinates of active sites for binding.
5. Performed docking using the default search parameters.
6. Analyzed the predicted binding modes and docking scores.

---

# Results

- Protein: Human Acetylcholinesterase (4BDT)
- Ligand: Acetylcholine
- Docking Software: SwissDock
- Best AC Score: -26 *(from SwissDock results)*

The docking predicted several possible binding conformations, ranked according to their estimated binding energies.

---

# Repository Structure

```
.
├── README.md
├── protein/
│   └── 4BDT.pdb
├── ligand/
│   └── acetylcholine.*
├── results/
│   ├── docking_results
│   └── screenshots
└── images/
```

---

Through this project, I learned:

- Basics of molecular docking
- Protein structure preparation
- Ligand selection
- Using SwissDock for docking simulations
- Interpreting docking scores
- Visualizing predicted binding poses

---

# Disclaimer

This project is intended for educational purposes. Docking scores are computational predictions and should be validated through further computational analyses and experimental studies.

---

# References

- SwissDock
- RCSB Protein Data Bank
- Grosdidier A., Zoete V., Michielin O. *SwissDock: A protein-small molecule docking web service based on EADock DSS.*
- PrankWeb
  
---

# Author

Sameer Ahmed S

BS-MS Student - IISER TVM.
