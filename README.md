# Analysis of Calcium propagation velocity in Heart-on-Chip devices

[Jupyter notebook](ca_analysis.ipynb) used for analyzing Calcium propgation velocities from high-speed video microscopy data. Analysis of aligned cardiac microtissues, cultured in a Heart-on-Chip shown.
Extracted profiles are used to compose Fig. S2 in [Schneider et al. (2022)](https://doi.org/10.1016/j.mtbio.2022.100280).

### Purpose
Determine the signal onset time for each x-position along the muscle fiber. From the propagation along the fiber, the Calcium velocity is determined.

### Input
Video of fluorescence intensity, recorded at ~ 200 fps. Frames are saved as series of .tif-files in each folder.

### Output
Analysis in notebook produces following plots indicating the color-coded signal propagation and corresponding fit to determine the propagation velocity:
![raw_signalcomparison](/figs/raw_signalcomparison.png)
![pospol_propagation](/figs/pospol_propagation.png)
![pospol_fit](/figs/pospol_fit.png)
![negpol_propagation](/figs/negpol_propagation.png)
![negpol_fit](/figs/negpol_fit.png)


## Citation
Please cite **O. Schneider, A. Moruzzi, S. Fuchs, A. Grobel, H. S. Schulze, T. Mayr, and P. Loskill, [Fusing spheroids to aligned μ-tissues in a heart-on-chip featuring oxygen sensing and electrical pacing capabilities](https://doi.org/10.1016/j.mtbio.2022.100280), Materials Today Bio 15, 100280 (2022)** if you reuse some of the code for your own analysis.