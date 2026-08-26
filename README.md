# Discovery-of-lead free double perovskite-halide
This is machine learning workflow to discover novel lead free perovskite with thermodynamic stability and required  Shockley–Queisser limit band gap.

# Chemical-Genome Backward Mapping for Lead-Free Double Perovskites

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![DOI: Materials Today Physics Q1 Impact Factor 9.3](https://img.shields.io/badge/DOI-10.1016%2Fj.mtphys.2026.102180-blue)](https://doi.org/10.1016/j.mtphys.2026.102180)

This repository implements the multi-stage materials informatics and backward-mapping framework described in:

> **Backward mapping from target optoelectronic phenotypes to chemical genomes for the discovery of lead-free double perovskites**  
> *Materials Today Physics  Q1 Impact Factor 9.3*, 66 (2026) 102180. [https://doi.org/10.1016/j.mtphys.2026.102180](https://doi.org/10.1016/j.mtphys.2026.102180)


## Overview

Traditional materials discovery relies on  brute force. This pipeline maps target functional phenotypes backward onto chemical descriptor "genes" across 13,088 charge-balanced $A_2BB'X_6$ double perovskites using evolutionary-optimized surrogates, SHAP interpretability, and first-principles DFT validation. 


## Included Datasets, DFT Calculations & Plotting Files

This repository contains all raw computational datasets, processed workflow outputs, and publication-standard visual assets to enable complete reproducibility:

* **Thermodynamic & Kinetic Stability Data:**
  * Ground-state DFT structural relaxations (relaxed coordinates and cell parameters).
  * 0 K convex-hull distance calculations ($\Delta E_{\text{hull}} \le 25\text{ meV/atom}$).
  * Decomposition enthalpy assessments ($\Delta H$) calculated against competing binary decomposition pathways.
  * Canonical ($NVT$) 300 K *ab initio* molecular dynamics (AIMD) trajectory logs and energy envelopes.

* **Electronic & Optoelectronic Profiles:**
  * Raw data for GGA-PBE electronic band structures and projected density of states (PDOS).
  * Direction-resolved and direction-averaged carrier effective masses (m_e, m_h).
  * Static electronic dielectric constants.
  * Hydrogenic Wannier-Mott exciton binding energies ($\Delta E_{\text{xb}}$).

* **Optical Response Spectra:**
  * Frequency-dependent complex dielectric functions.
  * Optical absorption coefficient spectra.
  * Refractive indices and extinction coefficients.
  * Reflectivity spectra.
  * Electron energy-loss spectra.
  * Frequency-dependent optical conductivity spectra.

* **OriginPro Project Files & Visual Assets:**
  * Editable OriginPro (`.opju` / `.opj`) project files containing raw data layers and curve fittings.
  * High-resolution figure exports for descriptor correlation heatmaps, parity plots, and residual distributions.
  * Receiver operating characteristic (ROC) curves and SHAP feature attribution summary plots.
  * Simulated powder X-ray diffraction (XRD) patterns for structural fingerprinting.
