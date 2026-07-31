# Drug permeation through POPC bilayer
This tutorial aims to study the permeation of a drug molecule (acetaminophen) through a POPC lipid bilayer using transition tempered metadynamics (TTMetaD) simulation. The complete system (drug + POPC bilayer + water) are assembled using CHARMM-GUI. We have used CHARMM36m force field parameters to calculate the forces and hence study the time evolution of the system. The complete study consists of the following steps:
1. Assemble the system (drug + POPC bilayer + water) using CHARMM-GUI
2. Energy Minimization of the system using GROMACS
3. NVT and NPT equilibration of the system using GROMACS
4. Production run for the stable system using GROMACS
5. TTMetaD simulation using GROMACS + PLUMED
6. Analyzing the free energy surface and computing the free energy profile (FEP) for the drug permeation through the lipid bilayer using PLUMED and zero-temperature string method 


