# Estimating potential-dependent physicochemical properties at metal--electrolyte interfaces using machine learning interatomic potentials
%![Graphical Abstract](TOC_Graphic.png)
This repository contains supporting material such as sample scripts used for calculations performed for our manuscript : **" Estimating potential-dependent physicochemical properties at metal--electrolyte interfaces using machine learning interatomic potentials"**. The repository also provides links to different Zenodo records containing the training and test datasets and all MACE and AIMD trajectories used in this work.

[![MIT License](https://img.shields.io/badge/Code-MIT-green.svg)](./LICENSE-CODE)
[![CC BY 4.0](https://img.shields.io/badge/Data-CC_BY_4.0-blue.svg)](./LICENSE-DATA)

## Below we provide links to three Zenodo records for this work
### 1. [Estimating potential-dependent physicochemical properties at metal--electrolyte interfaces using machine learning interatomic potentials (Part 1)](https://zenodo.org/uploads/17754595)
  - Training and Test Set (.tar) file contains multiple .extxyz files with all Density Functional Theroy (DFT) Single Point Calculation (SPC) data.
  - Within Training data contains .extxyz for all sytems with complete SPCs. Within traj_dir, I provided .extxyz used for training multiple iterations of MACE models with different size of training data.
  - Test data contains the DFT SPC.xyz files used for comparison against the MACE_model predicted .extxyz. the # next to model#.extxyz is the random seed used to generate respective model.
  - MACE models (.tar) folder contains final MACE models using for generating final trajectories. The folder number corresponds to the random seed. We use the MACE_swa_compiled.model for our work.
  - Benchmarking data (.tar) contains all AIMD and MACE trajectories used for benchmarking calculations for Au(111), Cu(111), and Rh(111) surfaces.
  - Au111_MACE_MD_2ns_trajectories.tar contains all final 2ns MACE-MD trajectories for Au(111) surfaces with different surface charge densities.
  - Au111_1NaCl_MACE_MD_1ns_trajectories.tar contains final 1ns MACE-MD trajectories for Au(111) surfaces with 1NaCl for $\sigma=0$.
  - Helping files (.tar) contain sample files used for analysis
### 2. [Estimating potential-dependent physicochemical properties at metal--electrolyte interfaces using machine learning interatomic potentials (Part 2)](https://zenodo.org/uploads/17756911)
  - Cu111_MACE_MD_2ns_trajectories.tar contains all final 2ns MACE-MD trajectories for Cu(111) surfaces with different surface charge densities.
  - Cu111_1NaCl_MACE_MD_1ns_trajectories.tar contains final 1ns MACE-MD trajectories for Cu(111) surfaces with 1NaCl for $\sigma=0$.
### 3. [Estimating potential-dependent physicochemical properties at metal--electrolyte interfaces using machine learning interatomic potentials (Part 3)](https://zenodo.org/uploads/17757050)
  - Rh111_MACE_MD_2ns_trajectories.tar contains all final 2ns MACE-MD trajectories for Rh(111) surfaces with different surface charge densities.
