# Teukolsky-equation-solutions-for-delta-function-source

### Description:
This repository provides numerical data associated with the paper "Resonance in black hole ringdown: Benchmarking quasinormal mode excitation and extraction" ([arXiv:2509.06411](https://arxiv.org/abs/2509.06411)).

The dataset includes numerical solutions to the Teukolsky equation sourced by a delta-function source. see also [Zenodo](https://doi.org/10.5281/zenodo.18511200).

### Contents:
- `/waveform/`: Contains numerical solutions of the Teukolsky equation for various parameters.
  - Time-domain strain waveform ($h$). Spanning $t \in [-100, 600]$ with a resolution of $\delta t = 10^{-2}$.
  - Time-domain Weyl scalar ($\Psi_4$). Spanning $t \in [-100, 600]$ with a resolution of $\delta t = 10^{-2}$.
  - Frequency-domain Weyl scalar ($\tilde{\Psi}_4$). Spanning $\omega \in [-4, 4]$ with a resolution of $\delta \omega = 10^{-3}$.
- `/data/`: Contains QNM excitation factor data (curated from Motohashi's dataset). Please note that the units in our dataset are defined as $M=1$, whereas the dataset uses $2M=1$.
- `example.ipynb`: A demonstration notebook showing that the quasi-normal mode amplitudes of the waveforms are consistent with the excitation factors.
