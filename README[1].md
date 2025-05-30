# Curvality Bayesian Validation: GW170817

This repository contains Bayesian inference notebooks comparing the Curvality entropy-curvature field theory to General Relativity using real LIGO data from the neutron star merger GW170817.

## Structure

- `notebooks/`
  - `Curvality_Model_GW170817.ipynb`: Runs full MCMC with entropy-curvature field theory (linked to the original Lagrangian)
  - `GR_Model_GW170817.ipynb`: Baseline GR-only Bayesian model
- `data/`
  - `curvality_residuals.csv`: Observed waveform residuals Δh(t)
- `results/`
  - `gr_summary.csv`, `gr_trace.png`: Posterior results from the GR model

## Instructions

1. Open either notebook in Google Colab
2. Upload the needed files when prompted
3. Run all cells
4. Compare outputs (posterior plots, residual fits, etc.)

## Manuscript

This repository supports the analysis in:  
**“Curvality: Entropy-Curvature Modulated Quantum Collapse from LIGO and Cosmological Data”**  
by Jake Brett

## License

MIT License – Free to use, reproduce, and modify for scientific purposes.
