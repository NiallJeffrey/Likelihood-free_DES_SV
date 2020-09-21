# Likelihood-free DES SV
### If you find the simulations or code useful, please cite:  "Likelihood-free inference with neural compression of DES SV weak lensing map statistics"; Jeffrey, Alsing, Lanusse '20: https://arxiv.org/abs/2009.08459


## Simulations
Included are the 74 independent convergence maps - each covering 1/8th of the sky (octant) - matched to the DES SV $n(z)$: https://github.com/NiallJeffrey/Likelihood-free_DES_SV/tree/master/simulations/original_lensing_maps

For each octant map, there are 17 derived DES SV mock shear and convergence maps: https://github.com/NiallJeffrey/Likelihood-free_DES_SV/tree/master/simulations/simulated_sv_maps

Examples of both of these are included in this notebook, along with a plot of the 74 associated cosmological parameters: https://github.com/NiallJeffrey/Likelihood-free_DES_SV/blob/master/simulations/plot_simulations_parameters.ipynb

## Example pyDELFI code
The data and code needed to perform the likelihood-free inference with the joint power spectrum and peak count summary statistics are shown in this directory: https://github.com/NiallJeffrey/Likelihood-free_DES_SV/tree/master/example_lfi

The example notebook uses the pyDELFI ([Alsing et al. 2019](https://arxiv.org/abs/1903.00007)) package: https://github.com/justinalsing/pydelfi
