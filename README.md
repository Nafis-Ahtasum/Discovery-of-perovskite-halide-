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


## Included Datasets, DFT Calculations & Plotting Files

This repository contains all raw computational datasets, processed workflow outputs, and publication-standard visual assets to enable complete reproducibility:

* **Thermodynamic & Kinetic Stability Data:**
  * Ground-state DFT structural relaxations (relaxed coordinates and cell parameters)[cite: 1].
  * 0 K convex-hull distance calculations ($\Delta E_{\text{hull}} \le 25\text{ meV/atom}$)[cite: 1].
  * Decomposition enthalpy assessments ($\Delta H$) calculated against competing binary decomposition pathways[cite: 1].
  * Canonical ($NVT$) 300 K *ab initio* molecular dynamics (AIMD) trajectory logs and energy envelopes[cite: 1].

* **Electronic & Optoelectronic Profiles:**
  * Raw data for GGA-PBE electronic band structures and projected density of states (PDOS)[cite: 1].
  * Direction-resolved and direction-averaged carrier effective masses ($m_e^*$, $m_h^*$)[cite: 1].
  * Static electronic dielectric constants ($\epsilon_1(0)$)[cite: 1].
  * Hydrogenic Wannier-Mott exciton binding energies ($\Delta E_{\text{xb}}$)[cite: 1].

* **Optical Response Spectra:**
  * Frequency-dependent complex dielectric functions ($\epsilon_1(\omega), \epsilon_2(\omega)$)[cite: 1].
  * Optical absorption coefficient spectra ($\alpha(\omega)$)[cite: 1].
  * Refractive indices ($n(\omega)$) and extinction coefficients ($\kappa(\omega)$)[cite: 1].
  * Reflectivity spectra ($R(\omega)$)[cite: 1].
  * Electron energy-loss spectra ($L(\omega)$)[cite: 1].
  * Frequency-dependent optical conductivity spectra ($\sigma_1(\omega)$)[cite: 1].

* **OriginPro Project Files & Visual Assets:**
  * Editable OriginPro (`.opju` / `.opj`) project files containing raw data layers and curve fittings.
  * High-resolution figure exports for descriptor correlation heatmaps, parity plots, and residual distributions[cite: 1].
  * Receiver operating characteristic (ROC) curves and SHAP feature attribution summary plots[cite: 1].
  * Simulated powder X-ray diffraction (XRD) patterns for structural fingerprinting[cite: 1].
