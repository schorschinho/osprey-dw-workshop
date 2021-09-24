# Osprey Practical Demonstration - DW-MRS-Workshop Leiden 2021

This repository contains exemplary material and interactive practical exercise notebooks on the use of the FID-A and the Osprey software, as presented in hybrid format at the “Best practices and tools for Diffusion MR Spectroscopy” workshop, taking place at the Lorentz center in Leiden (NL) in September 2021.

The Osprey software and SPM12 software are distributed under the licenses in the respective folders.

There is no licensure restriction on the practical exercise notebooks.

## Practical Exercise Notebooks

The repository should contain all code and data required to execute the following three interactive live script notebooks:

### 01 - FID_A_Sandbox.mlx

A MATLAB live script that introduces the [FID-A toolbox for modular analysis of MRS data](https://github.com/cic-methods/fid-a), explains the basic data storage structure, outlines a simple analysis workflow, and includes a few exercises to explore.

### 02 - Osprey_Walkthrough.mlx

This live script includes an introduction to the setup, structure, and use of the [Osprey software, an automated end-to-end workflow for in-vivo MRS data](https://github.com/schorschinho/osprey). The walkthrough features the execution of all key Osprey modules (Job, Load, Process, Fit, Coregistration, Segmentation, Quantify, GUI).

### 02 - dwMRS_with_Osprey.mlx

This live script shows an example workflow for analyzing diffusion-weighted MRS using Osprey. This showcases the full integration of the [LCModel software](http://s-provencher.com/lcmodel.shtml) into the fitting process, enabling diffusion-weighted MRS users to port some established analysis workflows over to Osprey.

## Additional material

### InVivo-Data, Synthetic-Data
In-vivo and simulated diffusion-weighted MRS data created by the organizing committee of the workshop, [available on GitHub](https://github.com/dwmrshub/pregame-workshop-2021).

### spm12
The [SPM12 software](https://github.com/spm/spm12) is created by a large team at University College London (UCL), UK.

### osprey-dwmrs
Temporary development version of the [Osprey software](https://github.com/schorschinho/osprey), specifically hand-crafted for the workshop. This is a work-in-progress - best practices and pipelines agreed on during the workshop will be incorporated into future main release versions.

### osprey-develop
Copy of the latest 'develop' branch (as of Sept 22 2021) of the [Osprey software](https://github.com/schorschinho/osprey). Please follow the main Osprey repository for frequent updates and new releases.

### README.MD
This file.
