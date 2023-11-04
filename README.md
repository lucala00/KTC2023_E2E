# Code for KTC2023 EIT challenge (End-to-end approach)


## Brief description of the algorithm
This repository contains the Python files required by the organisers of the EIT Kuopio challenge 2023 which implements an end-to-end approach.
Training was performed with GT simulated data with random polygons of different shapes and postive/negative contrast.

## Authors:
- Tatiana Bubba, University of Bath, UK, tab73 AT bath.ac.uk
- Luca Calatroni, CNRS, FR, calatroni AT i3s.unice.fr
- Damiana Lazzaro, University of Bologna, IT, damiana.lazzaro AT unibo.it 
- Serena Morigi, University of Bologna, IT, serena.morigi AT unibo.it 
- Luca Ratti, University of Bologna, IT, luca.ratti5 AT unibo.it
- Matteo Santacesaria, University of Genoa, IT, matteo.santacesaria AT unige.it 
- Julian Tachella, CNRS, FR, julian.tachella AT ens-lyon.fr

## Installation instructions and requirements

For installation and required environment see the environment_pnp.yml to restore the conda enviroment used for the submission. 
You can create the enviroment using the following command:

```conda env create -f environment.yml```

We created a script main.py to reconstruct the inclusions provided for training from voltage measurements:

```python main.py /path_to_input_folder /path_to_ouput_folder difficulty_level```
