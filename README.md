=================================================================================
"Aggregation patterns of curcumin and piperine mixtures in different polar media"
=================================================================================


J. R. C. Santos, P. E. Abreu, and J. M. C. Marques



DESCRIPTION OF FILES:



===================
GAMMES INPUT FILES:
===================
"curek-gam.inp"  - GAMMES input file for curcumin enol molecule
"curkk-gam.inp"  - GAMMES input file for curcumin keto molecule
"pip-gam.inp"    - GAMMES input file for piperine molecule



====================
GROMACS INPUT FILES:
====================
Each directory corresponds to each system used in the MD simulations:
PIP refers to piperine
CEK refers to curcumin enol
CKK refers to curcumin keto
The number of molecules used of each molecule is also indicated.
For example, 2CEK+2PIP corresponds to a simulation of 2 curcumin enol molecules and 2 piperine molecules.

GROMACS input files, including the Molecular dynamics parameters, to run MD Simulations:
(see GROMACS users manual for more info https://manual.gromacs.org/documentation/2019/index.html)
"minim.mdp" - input parameter file to run the energy minimization
"nvt.mdp"   - input parameter file to run the temperature equilibration (NVT)
"npt.mdp"   - input parameter file to run the pressure equilibration (NPT)
"md.mdp"    - input parameter file to run the main MD trajectory

Parameters and coordinates for each system:
(where "system" corresponds to the system used, and molecule to the molecule used)
"molecule.gro"       - atom coordinates for each individual molecule
"molecule.itp"       - topology file for a particular molecule including the forcefield parameters 
"molecule_atoms.itp" - atomtypes file used in the simulation
"system.pdb"         - atom coordinates for the system used in the simulation
"topol.top"          - topology file used in the simulation



For help and support please contact: qtmarque@ci.uc.pt

GAMESS is freeware downloadable from https://www.msg.chem.iastate.edu/gamess/
GROMACS is freeware downloadable from https://www.gromacs.org/
