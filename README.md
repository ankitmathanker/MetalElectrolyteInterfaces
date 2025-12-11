# Estimating potential-dependent physicochemical properties at metal--electrolyte interfaces using machine learning interatomic potentials
%![Graphical Abstract](TOC_Graphic.png)
This repository contains supporting material such as sample scripts used for calculations performed for our manuscript : **" Estimating potential-dependent physicochemical properties at metal--electrolyte interfaces using machine learning interatomic potentials"**. The repository also provides links to different Zenodo libraries containing the training and test datasets and all MACE and AIMD trajectories used in this work.

[![MIT License](https://img.shields.io/badge/Code-MIT-green.svg)](./LICENSE-CODE)
[![CC BY 4.0](https://img.shields.io/badge/Data-CC_BY_4.0-blue.svg)](./LICENSE-DATA)

## Repository Structure

### 1. [ITP_files](./itp_files/)
This folder contains .itp files (molecular topology) for different organics used in the study.

### 2. [Adsorption](./adsorption_sample.tar.xz)
The tar file consists of a sample calculation set-up for adsorption study performed in this work. It consists of four sub-folder namely **analysis**, **MDP**, **PMF**, **System**, and **UMs**.

- **System** folder contains following files:
  - sys#.gro files where # can be anything from 1 to 16. Each of these sys#.gro file consist of system structure with phenol at a distance away from the surface.
  - phenol.itp file consist of the molecular topology for phenol
  - topol.top file consists of main topology file for simulation. It includes various .itp files, includes atomtypes, nonbonded-parameters, and lists all molecules and their counts
  - index.ndx file consists of custom atom groups for analysis and restraints used in the simulation which makes it easy to reference a sub-group of atoms.
  - make_gro folder consists of various files used to create initial sys#.gro files.
