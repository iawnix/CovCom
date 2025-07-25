# CovCom
CovCom mainly relies on BioPython and RDKit. First, it uses BioPython to extract the residue atoms within 25 angstroms around the modification site and convert them into a format recognizable by RDKit. Next, RDKit is employed to splice the modified residues with the modified molecule, and a simple geometric optimization of the modified part is carried out based on the MMFF94 force field. Finally, the atomic coordinates of the modified part are refined by simulated annealing to optimize the binding pose of the new molecule within the cavity formed by surrounding residue atoms within 25 Å

![](image/covcom.png)
