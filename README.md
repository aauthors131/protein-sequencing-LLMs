# Protein-Sequencing

This repository contains all the code associated with the "Peptide Sequencing Via Protein Language Models" manuscripts.

## Settings

The latest Conda environment configuration is available in `conda_environments.txt`.

*Note:* This repository does not include executables or software such as TMscore.cc, OpenStructure's lDDT, or the AlphaFold Docker. Please refer to the respective authors of these applications for installation instructions.

## Usage

The code is organized in the **src/** folder and divided into different categories: `data`, `training-and-inference`, and `analysis`.

To run the code on your local machine, you will need to modify the appropriate variables.

This work was conducted on a DGX A100 system with the following specifications:
- Driver Version: 535.161.07
- NVIDIA-SMI: 535.161.07
- CUDA Version: 12.2

Due to size constraints, the results are not included, except for the structure analysis, which can be found in **src/analysis/full_structure_result.json**.