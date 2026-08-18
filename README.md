# **In-Silico Screening and Molecular Docking of Medicinal Phytochemicals Against HER2 in Breast Cancer**

# **Project Overview**



* This project applies a computational drug discovery workflow to screen medicinal phytochemicals against HER2 (ERBB2), a clinically relevant therapeutic target in breast cancer.



* The workflow integrates pathway analysis, therapeutic target identification, compound screening, ADMET evaluation, toxicity prediction, molecular docking, and protein–ligand interaction analysis to prioritize a potential lead phytochemical.



### Objective



To identify and prioritize a promising medicinal phytochemical against HER2 using an integrated bioinformatics and structure-based virtual screening workflow.



### Dataset

Screening Stage	Number of Compounds

Initial phytochemicals collected	    	- 76

Compounds screened using ADMET \& ProTox	    	- 60

Compounds selected for docking	            	- 12

Top-ranked compound	                    	- Kaempferol



### Workflow



#### Disease \& Pathway Analysis



→ Therapeutic Target Identification

→ Phytochemical Collection

→ ADMET Screening

→ Toxicity Prediction

→ Molecular Docking

→ Protein–Ligand Interaction Analysis

→ Final Compound Prioritization



### Methodology



##### 1\. Disease and Pathway Analysis



Breast cancer-associated pathways were investigated using the KEGG database to understand disease-related molecular mechanisms and identify relevant therapeutic targets.



##### 2\. Therapeutic Target Identification



The Therapeutic Target Database (TTD) was used to investigate therapeutic targets associated with breast cancer. HER2 (ERBB2) was selected for subsequent structure-based analysis.



##### 3\. Phytochemical Collection



A dataset of 76 medicinal phytochemicals was compiled using chemical databases and relevant literature. Compound structures and canonical SMILES were obtained for computational screening.



##### 4\. ADMET Screening



SwissADME was used to evaluate physicochemical, pharmacokinetic, drug-likeness, and ADMET-related properties. The compounds were assessed using predefined screening and scoring criteria.



##### 5\. Toxicity Prediction



ProTox was used for in-silico toxicity prediction. Toxicity profiles were considered alongside ADMET results to prioritize compounds for molecular docking.



##### 6\. Molecular Docking



The 12 prioritized compounds were docked against the prepared HER2 target using PyRx. Compounds were ranked according to their predicted docking affinity.



##### 7\. Lead Compound Identification



Kaempferol achieved the highest predicted docking affinity among the screened compounds:



Docking affinity: −6.5 kcal/mol



Kaempferol was therefore selected as the top-ranked compound for further protein–ligand interaction analysis.



##### 8\. Protein–Ligand Interaction Analysis



The Kaempferol–HER2 complex was analyzed using BIOVIA Discovery Studio Visualizer and molecular visualization to characterize the binding mode and interacting amino acid residues.



The corresponding 2D interaction diagram and 3D binding pose are available in:



05\_Interaction\_Analysis/



##### 9\. Final Compound Prioritization



### Final prioritization integrated:



ADMET profile

Toxicity prediction

Molecular docking affinity

Protein–ligand interaction analysis



Based on the integrated computational screening, Kaempferol was prioritized as the top-ranked phytochemical candidate for further investigation.





The complete docking ranking, compound prioritization data, and supporting figures are available in:



06\_Results/



### Tools and Databases



##### Databases



1. KEGG — Disease and pathway analysis
2. Therapeutic Target Database (TTD) — Therapeutic target identification
3. PubChem — Compound information and chemical structures
4. PubMed — Literature retrieval
5. Protein Data Bank (PDB) — Protein structure retrieval



##### Computational Tools



1. SwissADME — ADMET and drug-likeness analysis
2. ProTox — Toxicity prediction
3. PyRx — Molecular docking
4. BIOVIA Discovery Studio Visualizer — Protein–ligand interaction analysis
5. PyMOL — Molecular visualization and structural analysis



###### Repository Structure



01\_Data/

02\_ADMET/

03\_ProTox/

04\_Docking/

05\_Interaction\_Analysis/

06\_Results/

README.md

Project\_Report.docx

Limitations and Future Work



This study is based on in-silico predictions and therefore provides preliminary evidence rather than experimental confirmation.



Future work could include:



\~ Molecular dynamics simulations

\~ Binding free-energy calculations

\~ Further structural validation

\~ In-vitro biological validation

\~ Experimental evaluation of the prioritized phytochemical



###### Project Report



The complete methodology, datasets, analysis, results, figures, and supporting information are available in:



Project\_Report.docx



##### Author



*Poornimashanmugam*

