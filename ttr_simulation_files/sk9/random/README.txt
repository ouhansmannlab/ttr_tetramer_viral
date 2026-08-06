This directory contains initial and final pdb structures, parameter files, and topology files used in ttr-sk9 random simulation. Sk9 binds to 3-4 monomer-monomer interface of ttr at the begining of the simulation.
Starting conformation was obtained by performing docking calculations assigning the active residues randomly spread over the entire TTR surface.

sk9_random_initial.gro - Initial structure of ttr-sk9 random simulation
sk9_random_final.pdb - Final structure of ttr-sk9 random simulation

ions.mdp  ; Parameter file for ion addition
minim.mdp ; Parameter file for energy minimization
nvt.mdp   ; Parameter file for NVT equilibration
npt.mdp   ; Parameter file for NPT equilibration
md.mdp 	  ; Parameter file for production MD run

topol.top ; Topology file of the system

topol_Protein_chain_A.itp-topol_Protein_chain_D.itp ; Topology file of individual chain in ttr
posre_Protein_chain_A.itp-posre_Protein_chain_D.itp ; Position restraint files for individual chain in the ttr tetramer 

topol_Protein_chain_E.itp ; Topology file of the sk9 fragment
posre_Protein_chain_E.itp ; Position restraint file of sk9 fragment
























