# Discovery-of-lead free double perovskite-halide
This is machine learning workflow to discover novel lead free perovskite with thermodynamic stability and required  Shockley–Queisser limit band gap.

# Chemical-Genome Backward Mapping for Lead-Free Double Perovskites

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![DOI: Materials Today Physics](https://img.shields.io/badge/DOI-10.1016%2Fj.mtphys.2026.102180-blue)](https://doi.org/10.1016/j.mtphys.2026.102180)

This repository implements the multi-stage materials informatics and backward-mapping framework described in:

> **Backward mapping from target optoelectronic phenotypes to chemical genomes for the discovery of lead-free double perovskites**  
> *Materials Today Physics*, 66 (2026) 102180. [https://doi.org/10.1016/j.mtphys.2026.102180](https://doi.org/10.1016/j.mtphys.2026.102180)


## Overview

Traditional materials discovery relies on  brute force. This pipeline maps target functional phenotypes backward onto chemical descriptor "genes" across 13,088 charge-balanced $A_2BB'X_6$ double perovskites using evolutionary-optimized surrogates, SHAP interpretability, and first-principles DFT validation. 


Included Datasets, DFT Calculations & Plotting FilesThis repository includes all raw data, processed outputs, and visual assets necessary for full reproducibility:Thermodynamic & Kinetic Stability Data: Complete DFT ground-state structural relaxations, 0 K convex-hull distance calculations ($\Delta E_{\text{hull}} \le 25\text{ meV/atom}$), decomposition enthalpy assessments ($\Delta H$) against competing binary phases, and 300 K ab initio molecular dynamics (AIMD) trajectory logs.  Electronic & Optoelectronic Profiles: Raw data for GGA-PBE electronic band structures, projected density of states (PDOS), direction-resolved carrier effective masses ($m_e^*$, $m_h^*$), static dielectric constants ($\epsilon_1(0)$), and hydrogenic Wannier-Mott exciton binding energies ($\Delta E_{\text{xb}}$).  Optical Response Spectra: Frequency-dependent complex dielectric functions ($\epsilon_1, \epsilon_2$), optical absorption coefficients ($\alpha(\omega)$), refractive indices ($n(\omega)$), extinction coefficients ($\kappa(\omega)$), reflectivity spectra ($R(\omega)$), electron energy-loss functions ($L(\omega)$), and optical conductivity profiles ($\sigma_1(\omega)$).  OriginPro Project Files & Figures: High-resolution figures, correlation heatmaps, parity plots, simulated powder XRD diffraction fingerprints, and editable OriginPro (.opju / .opj) project files used to generate all publication-quality analytical plots.  
