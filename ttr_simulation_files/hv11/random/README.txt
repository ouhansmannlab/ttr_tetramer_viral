This directory contains initial and final pdb structures, parameter files, and topology files used in ttr-hv11 random simulation. Hv11 binds to 3-4 monomer-monomer interface of ttr at the begining of the simulation.
Starting conformation was obtained by performing docking calculations assigning the active residues randomly spread over the entire TTR surface.

hv11_random_initial.gro - Initial structure of ttr-hv11 random simulation
hv11_random_final.pdb - Final structure of ttr-hv11 random simulation

ions.mdp  ; Parameter file for ion addition
minim.mdp ; Parameter file for energy minimization
nvt.mdp   ; Parameter file for NVT equilibration
npt.mdp   ; Parameter file for NPT equilibration
md.mdp 	  ; Parameter file for production MD run

topol.top ; Topology file of the system

topol_Protein_chain_A.itp-topol_Protein_chain_D.itp ; Topology file of individual chain in ttr
posre_Protein_chain_A.itp-posre_Protein_chain_D.itp ; Position restraint files for individual chain in the ttr tetramer 

topol_Protein_chain_E.itp ; Topology file of the hv11 fragment
posre_Protein_chain_E.itp ; Position restraint file of hv11 fragment
























