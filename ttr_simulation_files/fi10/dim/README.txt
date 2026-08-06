This directory contains initial and final pdb structures, parameter files, and topology files used in ttr-fi10 dim simulation. Fi10 binds to dimer-dimer interface of ttr at the begining of the simulation.

fi10_dim_initial.pdb - Initial structure of ttr-fi10 dim simulation
fi10_dim_final.pdb - Final structure of ttr-fi10 dim simulation

ions.mdp  ; Parameter file for ion addition
minim.mdp ; Parameter file for energy minimization
nvt.mdp   ; Parameter file for NVT equilibration
npt.mdp   ; Parameter file for NPT equilibration
md.mdp 	  ; Parameter file for production MD run

topol.top ; Topology file of the system

topol_Protein_chain_A.itp-topol_Protein_chain_D.itp ; Topology file of individual chain in ttr
posre_Protein_chain_A.itp-posre_Protein_chain_D.itp ; Position restraint files for individual chain in the ttr tetramer 

topol_Protein_chain_E.itp ; Topology file of the fi10 fragment
posre_Protein_chain_E.itp ; Position restraint file of fi10 fragment
























