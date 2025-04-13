# Overview

We use amino acid sequences to construct music.  The frequency of the amino acid and its seconday structure is used to construct the harmony while the sequence itself is used to construct the melody.

# Creating Music

Music is currently constructed for the [TENT2](https://www.rcsb.org/structure/6LBJ) protein.  You can use different proteins specified by their
* PDB protein ID (e.g. 6LBJ for TENT2)
* protein secondary structure `dssp` file: can be accessed [here](https://pdb-redo.eu/dssp) using the PDB protein ID.

Then just set the variable `protein_ID` to the PDB protein ID, add the `{portein_ID}.dssp` file to the `protein_surface_files` folder and run the notebook `main.ipynb`!
