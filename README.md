[![Paper](https://img.shields.io/badge/paper-arXiv%3A2201.04155-B31B1B.svg)](https://arxiv.org/abs/2201.04155)
[![DOI](https://zenodo.org/badge/396873415.svg)](https://zenodo.org/badge/latestdoi/396873415)

# A Parameter-Free Differential Evolution Algorithm for the Analytic Continuation of Imaginary Time Correlation Functions

Nathan S. Nichols, Paul Sokol, Adrian Del Maestro

[arXiv:2201.04155](https://arxiv.org/abs/2201.04155)

### Abstract
We report on Differential Evolution for Analytic Continuation (DEAC): a parameter-free evolutinary algorithm to generate the dynamic structure factor from imaginary time correlation functions. Our approach to this long-standing problem in quantum many-body physics achieves enhanced spectral fidelity while using fewer compute (CPU) hours. The need for fine-tuning of algorithmic control parameters is eliminated by embedding them within the genome to be optimized for this evolutionary computation based algorithm.  Benchmarks are presented for models where the dynamic structure factor is known exactly, and experimentally relevant results are included for quantum Monte Carlo simulations of bulk $^4$He below the superfluid transition temperature. 

### Description
This repository includes links, code, scripts, and data to generate the figures in a paper.

### Requirements
The data in this project was generated via path integral quantum Monte Carlo (QMC) and analytic continuation techniques.  Everything included in the [data](https://github.com/DelMaestroGroup/papers-code-DEAC/tree/main/data) directory was generated via:

* [DEAC: A C++ implementaion of the differential evolution for analytic continuation algorithm](https://github.com/nscottnichols/deac-cpp)
* [DEAC.jl: A Julia implementaion of the differential evolution for analytic continuation algorithm](https://github.com/nscottnichols/DEAC.jl)
* [FESOM.jl: A Julia implementaion of the fast and efficient stochastic optimization method](https://github.com/nscottnichols/FESOM.jl)
* [MEM.jl: A Julia implementaion of the maximum entropy method](https://github.com/nscottnichols/MEM.jl)
* [PIMC: A C++ path integral quantum Monte Carlo implementation](https://code.delmaestro.org/)

### Support
The creation of these materials was supported in part by the National Science Foundation under Award Nos. DMR-1809027 and
DMR-1808440.

[<img width="100px" src="https://www.nsf.gov/images/logos/NSF_4-Color_bitmap_Logo.png">](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1809027)
[<img width="100px" src="https://www.nsf.gov/images/logos/NSF_4-Color_bitmap_Logo.png">](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1808440)

### Figures

#### Figure 01: A schematic representation of the method to determine the optimal regularization constant when using the maximum entropy approach.
<img src="https://github.com/DelMaestroGroup/papers-code-DEAC/blob/main/figures/maxent_cartoon.svg" width="400px" style="background-color:white;padding:20px;">

This figure is released under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) and can be freely copied, redistributed and remixed.

#### Figure 02: Nine different spectral reconstructions using different analytic continuation methods on simulated quantum Monte Carlo data.
<img src="https://github.com/DelMaestroGroup/papers-code-DEAC/blob/main/figures/nine_panel_small.svg" width="800px" style="background-color:white;padding:20px;">

This figure is released under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) and can be freely copied, redistributed and remixed.

#### Figure 03: Analytic continuation results using DEAC, FESOM, and MEM for the *tso* case at *medium* error level.
<img src="https://github.com/DelMaestroGroup/papers-code-DEAC/blob/main/figures/tso_medium.svg" width="400px" style="background-color:white;padding:20px;">

This figure is released under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) and can be freely copied, redistributed and remixed.

#### Figure 04: CPU time required to generate the final spectra using each analytic continuation technique.
<img src="https://github.com/DelMaestroGroup/papers-code-DEAC/blob/main/figures/CPU_time_large.svg" width="400px" style="background-color:white;padding:20px;">

This figure is released under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) and can be freely copied, redistributed and remixed.

#### Figure 05: Population size scaling for the DEAC algorithm performing analytic continuation of the tsc case at large error level.
<img src="https://github.com/DelMaestroGroup/papers-code-DEAC/blob/main/figures/population_scaling.svg" width="400px" style="background-color:white;padding:20px;">

This figure is released under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) and can be freely copied, redistributed and remixed.

#### Figure 06 (top): The phonon-roton spectrum of helium-4 at T=1.56K from neutron scattering experiments on superfluid helium.
<img src="https://github.com/DelMaestroGroup/papers-code-DEAC/blob/main/figures/bulk_he_spectrum_sokol.svg" width="400px" style="background-color:white;padding:20px;">

This figure is released under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) and can be freely copied, redistributed and remixed.

#### Figure 06 (bottom): The phonon-roton spectrum of helium-4 at T=1.35K as generated by DEAC from canonical quantum Monte Carlo data (bottom).
<img src="https://github.com/DelMaestroGroup/papers-code-DEAC/blob/main/figures/bulk_he_spectrum.svg" width="400px" style="background-color:white;padding:20px;">

This figure is released under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) and can be freely copied, redistributed and remixed.

#### Figure 07: Maximum peak locations for the helium-4 dispersion at T=1.35 as generated by analytic continuation of QMC data using the DEAC algorithm.
<img src="https://github.com/DelMaestroGroup/papers-code-DEAC/blob/main/figures/helium_dispersion.svg" width="400px" style="background-color:white;padding:20px;">

This figure is released under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) and can be freely copied, redistributed and remixed.
