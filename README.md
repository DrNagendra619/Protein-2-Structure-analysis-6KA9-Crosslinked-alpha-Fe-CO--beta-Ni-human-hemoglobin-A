# Protein-2-Structure-analysis-6KA9-Crosslinked-alpha-Fe-CO--beta-Ni-human-hemoglobin-A
Protein 2° Structure analysis 6KA9 = Crosslinked alpha(Fe-CO)-beta(Ni) human hemoglobin A in the T quaternary structure at 95 K: Dark 
# Human Hemoglobin A (PDB ID: 6KA9) Structural and Predictive Analysis 🩸🔬

## Overview

This project provides a multi-tool analysis of the structure of **Human Hemoglobin A (HbA)**, focusing on the PDB entry **6KA9** (a cross-linked $\alpha$-Fe(CO) $\beta$-Ni complex). The repository combines visualization files, homology modeling results, and theoretical secondary structure predictions to offer a complete view of this critical protein.

### Analysis Goals
1.  Store and organize the experimental 3D structure and its FASTA sequence.
2.  Generate and assess a **Homology Model** of the Hemoglobin alpha subunit (HbA $\alpha$).
3.  Predict the **Secondary Structure** ($\alpha$-helices, $\beta$-sheets, coils) using computational methods.
4.  Visualize the structure and confirm predictive accuracy using multiple tools (PyMOL, SWISS-MODEL, GOR4, Phyre).

---

## Repository Files and Methods

| File Name | Method/Tool | Purpose |
| :--- | :--- | :--- |
| `rcsb_pdb_6KA9.fasta` | **Input Data** | FASTA sequence file for the $\alpha$ and $\beta$ subunits of Human Hemoglobin A (PDB ID 6KA9). |
| `6KA9 pymol file.pse` | **Visualization** (PyMOL) | A **PyMOL Session file** containing the loaded 3D structure (6KA9) and pre-set views for analysis. |
| `Hemoglobin alpha subuniT model swiss model file.pdb` | **Homology Modeling** (SWISS-MODEL) | The predicted 3D structure for the $\alpha$-subunit, likely including the Heme molecule. |
| `NPS@ _ GOR4 SECONDARY STRUCTURE PREDICTION RESULTS.pdf` | **Secondary Structure Prediction** (GOR4) | Detailed PDF report showing the predicted percentage and location of $\alpha$-helices and random coils for the subunit sequence. |
| `Phyre results .png` | **Secondary Structure Prediction** (Phyre) | Visualization output confirming the prediction success and high confidence of the tertiary structure model. |

---

## Structural and Prediction Insights

### 1. Structure (PDB: 6KA9)
* **Protein:** Human Hemoglobin A ($\alpha_2\beta_2$ heterotetramer).
* **Key Feature:** The structure includes essential ligands (Heme groups) and is characterized by a high percentage of **$\alpha$-helices**, consistent with the globin fold.

### 2. Secondary Structure Prediction (GOR4)
The GOR4 analysis provides a statistical breakdown of the secondary structure elements (SSEs):

| SSE Type | Percentage | Finding |
| :--- | :--- | :--- |
| **Alpha helix (Hh)** | **~60.99%** | Confirms the dominant helical nature of the globin fold. |
| **Extended strand (Ee)** | ~4.26% | Minimal $\beta$-sheet content. |
| **Random coil (Cc)** | ~34.75% | Regions of flexible loops and turns. |

### 3. Tertiary Structure Modeling (SWISS-MODEL/Phyre)
* The **Homology Model** of the alpha subunit (`Hemoglobin alpha subuniT model swiss model file.pdb`) is highly accurate due to the abundance of highly homologous Hemoglobin structures available as templates.
* The **Phyre** result visualization indicates a **high confidence level** (likely $100\%$ confidence and high coverage) for the overall 3D fold, confirming the structure can be reliably modeled.

---

## Setup and Usage

To explore the analysis and models in this repository:

1.  **Clone the repository:**
    ```bash
    git clone [Your Repository URL]
    cd [Your Repository Name]
    ```

2.  **Install Dependencies:**
    You need **PyMOL** to open the visualization session file and a PDF reader for the reports.
    ```bash
    # PyMOL is recommended for viewing 6KA9 pymol file.pse
    # No Python packages are needed for analysis of the output files.
    ```

3.  **View Results:**
    * **3D Structure:** Open `6KA9 pymol file.pse` in PyMOL to view the annotated tetrameric structure.
    * **Model:** Load `Hemoglobin alpha subuniT model swiss model file.pdb` into any viewer for the $\alpha$-subunit model.
    * **Secondary Structure:** Open the `NPS@ _ GOR4 SECONDARY STRUCTURE PREDICTION RESULTS.pdf` to examine the residue-by-residue GOR4 prediction.
