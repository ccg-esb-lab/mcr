# Theoretical Model of Compensatory Adaptation in Plasmid Dynamics

Scripts and data used to produce figures and simulations related to the theoretical model from:

**Persistence of mcr resistance following long-term absence of colistin selection in a biofilm environment**  
Wu et al.

## Overview

This repository contains the scripts and data for the theoretical model developed in our study, which investigates the dynamics of plasmid-bearing bacterial populations and compensatory adaptation under varying environmental conditions. The model, based on ordinary differential equations (ODEs), explores scenarios involving plasmid-bearing (*Bp*), plasmid-free (*B0*), and plasmid-adapted (*Ba*) cells competing for a single limiting resource. The numerical simulations assess how ecological factors and antibiotic selection pressures influence plasmid stability, bacterial population dynamics, and the role of compensatory mutations.

## Notebooks

1. **py-mcr_CurveFit.ipynb:**  
   This notebook calibrates the parameter models against experimental data. It fits Monod growth curves and estimates strain-specific parameters such as growth rates (ρ) and susceptibility coefficients (κ) using optical density (OD) and MIC data.

2. **py-mcr_Model_2strains.ipynb:**  
   This notebook simulates the stability of plasmids in a two-strain model, including plasmid-free (*B0*) and plasmid-bearing (*Bp*) populations under varying levels of antibiotic selection pressure.

3. **py-mcr_Model_3strains.ipynb:**  
   This notebook extends the model to include a plasmid-adapted (*Ba*) population, representing cells that have acquired compensatory mutations. It explores the long-term dynamics of the bacterial populations under different ecological and evolutionary scenarios.

## Authors
Carles Tardío Pi \\
Rafael Peña-Miller \\
[\@Systems Biology Lab, CCG-UNAM](https://github.com/ccg-esb-lab)

## License

[MIT](https://choosealicense.com/licenses/mit/)

This project is licensed under the MIT License - see the
[license.txt](/ccg-esb-lab/pBGT/blob/main/license.txt) file for details.
