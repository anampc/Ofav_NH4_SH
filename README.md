# Effect of elevated NH4 on *Orbicella faveolata* symbiont to host cell ratio (S/H)

[![DOI](https://zenodo.org/badge/doi/XXX/zenodo.XXX.svg)](http://dx.doi.org/XXX/zenodo.XXX)

This repository contains data and analysis scripts for the manuscript:

## Increased Algal Symbiont Density Reduces Host Immunity in a Threatened Caribbean Coral Species, *Orbicella faveolata*
#### Authors: Lauren E. Fuess, Ana M. Palacio-Castro, Caleb C. Butler, Andrew C. Baker, Laura D. Mydlarz
#### Journal: _Front. Ecol. Evol_ [doi:10.3389/fevo.2020.572942](https://doi.org/10.3389/fevo.2020.572942)  

-----

### Description:

This repository:

* Calculates the symbiont to host cell ratio (S/H) in *O. faveolata* corals, and
* Tests if corals exposed to elevated NH4 (N) present higher S/H than corals maintained under ambient concentrations (C) 

### Contents:
#### Scripts:
* **SH_script.Rmd:** R script that imports the real-time PCR (qPCR) data and 
calculates the S/H cell ratio using the StepOne program (https://github.com/jrcunning/steponeR).

#### Data:
* **Data:** Folder containing the amplification CTs for each coral sample obtained from the qPCR machine. 

* **Outputs:** Folder contained exported graphs (Figure 1), S/H cell ratio values and outputs of post-hoc Tukey comparisons. 

* **Sample_Plates.csv:** File containing the sample treatment information (Coral colony, treatment) and the qPCR plate were each sample was run. 
</br>


