# Codes for Mutation and Minimization (MuMi) Scheme

## Prerequisites:

- NAMD2 ([Download Link](https://www.ks.uiuc.edu/Research/namd/))
- VMD ([Download Link](https://www.ks.uiuc.edu/Research/vmd/))
- Python (Anaconda is recommended) ([Download Link](https://www.anaconda.com/download))
- Python packages: Numpy and ProDy ([ProDy Download](http://prody.csb.pitt.edu/))

**Note:** Ensure that all software is properly configured and added as path variables.

The MuMi scheme takes a PDB file (here *1fcc.pdb* as an example) and mutates all possible single mutations using NAMD2 and VMD. Mutant PDB files are first generated with ProDy, and minimizations are carried out using NAMD2 and VMD.

In the *MuMi_scheme.ipynb* Jupyter notebook, you can find detailed explanations for the code. This notebook also relies on *autopsf_batch.tcl* and *rtf* files.

If you encounter issues running *autopsf_batch.tcl* within the Jupyter notebook, you can execute this file in your working directory using the terminal.

Please keep in mind that this is a developing pipeline, and we are actively fixing bugs on a daily basis.

The codes are developed by [Tandac Furkan Guclu](https://github.com/tfguclu) .
