
# Life-Science
It's an AI guided article:
To understand sequence analysis &amp; phylogenetic and few more life science applications.


Some of the platforms & relavant databases:
- Molecule Viewer
- AlphaFold Databases (https://alphafold.ebi.ac.uk/)
- EMBL (https://www.embl.org/)
- RasTop
- Protein Data Bank (eg. 1a1a)
- Polyview 3D
- PLOS (Public Library of Science)



AlphaFold (Example Molecule View): 
- Protein : Probable disease resistance protein (This is the name or label of a protein. It is likely involved in disease resistance, which means it might help the plant defend itself against diseases.)
- Gene : At1g58602 (This is the unique identifier for the gene that codes for the mentioned protein. Genes are like instruction manuals for building proteins in living organisms.)
- Source organism : Arabidopsis thaliana (Mouse-ear cress) (Arabidopsis thaliana is a small flowering plant commonly used in scientific research. It's often referred to as Mouse-ear cress. In this case, it's the organism from which both the gene and protein originate.)



Refer Sample PDB File 
(Source: AlphaFold)

![image](https://github.com/vivekanandpkr/Life-Science/assets/21027388/fb884523-ea88-4ca5-9e75-b6497a53be68)

  Plant: (Arabidopsis thaliana)
  
  ![image](https://github.com/vivekanandpkr/Life-Science/assets/21027388/83523122-94fa-4140-a708-03ee4bd11b4b)


How to read this file content  ?

MODEL        1                                                                  
ATOM      1  N   MET A   1      -9.212  -5.798  33.490  1.00 63.75           N  
ATOM      2  CA  MET A   1     -10.075  -6.130  32.322  1.00 63.75           C 



For example:
Protein Data Bank (PDB) format which is commonly used to represent the three-dimensional structure of biological molecules, such as proteins. Each line in this format contains information about atoms and their positions in a molecule. Here's a breakdown of how to read the content:

MODEL 1: This line indicates that you are looking at the first model in the PDB file. In some cases, a structure might have multiple models to represent different conformations or snapshots of the molecule.

ATOM: This line represents an atom in the molecule.
- 1: Atom serial number.
- N: Atom name (in this case, it's the nitrogen atom).
- MET: The amino acid or molecule to which the atom belongs (in this case, it's methionine).
- A: Chain identifier (a protein can consist of multiple chains, and each chain is assigned a letter).
- 1: Residue sequence number (position of the amino acid in the chain).
- 9.212, -5.798, 33.490: X, Y, and Z coordinates of the atom's position in space.
- 1.00: Occupancy (typically set to 1.00).
- 63.75: Temperature factor (also known as B-factor, which represents the thermal motion of the atom).
- N: Element symbol (in this case, nitrogen)..


Source: Alphafold. 
Licence and attribution
Data is available for academic and commercial use, under a CC-BY-4.0 licence.



Slightly different scope here but healthcare related, we can also analyse the physicians availability per country as per WHO, available below: (Embedded & hosted from Tableau Public directly)

Created and submitted for Tableau IronViz  visualizations competitions 2022-2021 on Healthcare Challenges)          




