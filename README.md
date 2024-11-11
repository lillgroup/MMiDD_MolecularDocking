# Molecular Modeling in Drug Design - Molecular Docking
***

## Description

This repository contains the material used in molecular docking part of the Molecular Modeling in Drug Design lecture.

## Install

### Hardware requirements
  > Linux or MacOS or Windows


### Download Code and set up conda environment

The instructions are currently only for development and not the end users (students).

>1. Save repository into your home directory or dedicated folder \
`git clone https://github.com/lillgroup/MMiDD_MolecularDocking` 
>2. `cd MMiDD_MolecularDocking/install`
>3. Install miniconda if not already installed \
`sh install_conda.sh`
>4. Install the tutorial conda environment \
`conda env create -f environment.yml` 
>5. Activate environment \
`conda activate docking-2024`
>6. Connect the conda environment with the jupyter-notebook \
`python -m ipykernel install --user --name=docking-2024`


# Course

## For students
1. [Molecular Docking](MolecularDocking/MolecularDocking.ipynb)
2. [ROC curve pen and paper](ROC/Pen_and_paper.pdb)
3. [ROC Notebook](ROC/ROC.ipynb)
4. [VirtualScreening](VirtualScreening/VirtualScreening.ipynb)

### Solutions
1. [Molecular Docking](MolecularDocking/MolecularDocking_solution.ipynb)
4. [VirtualScreening](VirtualScreening/VirtualScreening_solution.ipynb)


## Further infos:
Contacts visualisation: https://cran.r-project.org/web/packages/NGLVieweR/vignettes/NGLVieweR.html