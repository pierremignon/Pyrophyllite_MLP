# Pyrophyllite_MLP

Atomistic Potential data for Neural Network Potentials to be used for the Pyrophyllite Material
directly with LAMMPS. The dataset used for the training has been computed from DFT/PBE Calculations
with VASP package using a cutoff Eerngy of 400 and 600 eV. File are provided for both potentials. 
Datasets are also provided allowing to train new potential from other neural netwrok atomistic 
potentials architextures (DeepMD, PhysNEt, ... ). This has bee developped by Sanz C.*, 
Allouche A.-R.*, Bousige C.**, Mignon P.* from *  Institut Lumière Matière and ** Laboratoire 
Multimatériaux et Interfaces at Université Claude Bernard Lyon 1, France. 

To be cited with : 
Title, Journal, Volume, Year, Sanz C., Allouche A.-R., Bousige C., Mignon P.

Includes the n2p2 atomistic potential files to be used directly with LAMMPS : 
- weights for H O Al Si
- input.nn
- scaling.data

Includes the dataset used for the n2p2 training that generated the n2p2 atomistic potential files:
- input.data

