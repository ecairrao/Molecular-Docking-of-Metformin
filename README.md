# Molecular-Docking-of-Metformin
In silico simulation between metfomin and estrogen receptors (ERalpha and ERbeta) and androgen receptors (AR)

This project is a computational approach enabling the binding simulation of metformin to the oestrogen receptors alpha and beta (ERα and ERβ) and androgen receptors (AR). 
Molecular Docking simulations were calculated using Lamarckian genetic algorithm from Autodock4 program (http://autodock.scripps.edu/). 

The 3D structures were obtained from Protein Data Bank (PDB): metformin (PDB ID: 5G5J), ERα (PBD ID: 1GWR), ERβ (PDB ID: 5TOA) and AR (PDB ID: 2PKL). 

DockPrep of the receptors and ligands were performed thought removing water molecules, merging non-polar hydrogen atoms, and adding Gasteiger partial charges using Autodock tools 1.5.6 and Chimera 1.15 software’s. 

The grid boxes constructed based on the coordinates of each crystal protein structure active centre (Autogrid 4, grid spacing 0.375 Å) were as follows (x, y, z):
AR - 20 x 26 x 10 Å
ERα - 21 x 8 x 30 Å
ERβ –14 x 32 x 14 Å

RMSD values <2 validated the molecular docking between the receptors and natural ligands.

The interaction between the metformin within the active centres of the desired proteins with the lowest Gibbs free binding energy (estimated as ΔG in kcal/mol) were analysed. 

The main atomic interactions were visualized with the UCSF Chimera (v. 1.15), Discovery Studio Visualizer (BIOVIA, v. 21.1.0.20298), and PyMOL (Molecular Graphics System, v. 2.3.2) software’s. 

Our main findings showed that metformin binds to androgen (AR) and oestrogen receptors (ERα and ERβ). Although metformin does not have a classic structure of EDC, nor has a very similar structure to DHT or E2, its activity as a polypharmacological agent, acting weakly on multiple targets induces a strong end effect, which may be the explanation for its adverse effects on human reproductive health. Our in-silico assays suggested that: 
1) Metformin has a potential to be an endocrine disruptor, acting mainly at ERα. 
2) Metformin heightened bonding preference toward Glu residues as demonstrated for ERα and ERβ simulations. 
3) Metformin may have a weak agonist activity on AR.
Further studies are needed to use metformin in pregnant women without impair the cardiovascular health of the future generation.

This repository contains all files to open and visualize these in silico simulations.

You can find more information in the following publication: “Protein interaction network for identifying vascular response of Metformin (antidiabetic oral)” - Manuscript ID: biomedinformatics-1634130, MPDI - BioMedInformatics, minor revisions. Last Updated at 10-03-2022
