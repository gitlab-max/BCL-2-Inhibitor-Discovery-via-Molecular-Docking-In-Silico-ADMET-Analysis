#BCL-2 Inhibitor Discovery via Molecular Docking & In-Silico ADMET Analysis

📌 Project Overview

This repository contains a computational drug discovery workflow targeting the BCL-2 anti-apoptotic protein, a key target in cancer research.

The study integrates:

Molecular docking
ADMET prediction
Toxicity profiling
Drug-likeness evaluation

Natural compounds were retrieved from the ZINC database and analyzed using multiple computational platforms.

⚙️ Workflow
1. Molecular Docking (Schrödinger Maestro)
Protein target: BCL-2
Ligand library: ZINC natural compounds
Output: Binding affinity ranking of top hits
2. ADMET Analysis

Performed using multiple tools:

🧪 SwissADME
🧪 Schrödinger QikProp
🧪 pkCSM

Key parameters evaluated:

Absorption (GI absorption, Caco-2 permeability)
Distribution (BBB permeability, plasma binding)
Metabolism (CYP interactions)
Excretion
Drug-likeness rules (Lipinski, Veber, etc.)
3. Toxicity Prediction

Performed using:

☠️ ProTox-3.0

Endpoints analyzed:

Hepatotoxicity
Cardiotoxicity
Mutagenicity
Immunotoxicity
Organ toxicity profiles
🏆 Key Results
Top docking score: -7.097 kcal/mol
Strong binding observed for selected ZINC compounds
High polarity and glycosylation observed across leads
Good solubility but low predicted oral absorption
No major PAINS alerts detected
⚠️ Key Insight

Glycosylated natural products showed strong docking interactions but reduced predicted GI absorption, highlighting a classic binding affinity vs pharmacokinetic trade-off.

🔬 Next Steps
Molecular Dynamics (MD) simulations
MM/GBSA binding free energy calculations
Aglycone vs glycosylated scaffold comparison
Lead optimization strategies
📁 Repository Contents
📂 docking_results/
📂 admet_qikprop/
📂 swissadme_results/
📂 pkcsm_results/
📂 prototox_results/
📂 figures/
README.md

🧠 Tools Used
Schrödinger Maestro (Docking)
QikProp (ADMET)
SwissADME (Drug-likeness)
pkCSM (Pharmacokinetics)
ProTox-3.0 (Toxicity)

📌 Conclusion

This project demonstrates a full in-silico pipeline for early-stage drug discovery, combining docking and multi-layer ADMET/toxicity filtering to prioritize lead candidates against BCL-2.

🔖 Keywords

#BCL2 #MolecularDocking #ADMET #DrugDiscovery #ComputationalChemistry #Bioinformatics #Schrodinger #SwissADME #pkCSM #ProTox #CancerResearch
