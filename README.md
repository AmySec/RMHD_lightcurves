# RMHD_lightcurves

Light curves from the multi-frequency radiation magentohydrodynamic simulations in Secunda et al. 2025. X-ray light curves are modeled using a damped random walk or power-law power spectral density (PSD) and are provided for comparison to the UV light curves. UV light curves are the reprocessed UV light curves emitted from the disks in our simulations.

Each file is labeled by run type and whether it contains an X-ray or UV light curve. Light curves have a standard and higher cadence version. The first column provides the time in days. Day zero is when we first begin injecting X-rays into the simulation. The second column provides the flux in code units. While the flux units are arbitrary the relative flux between different runs and light curves is consistent.

Files are labeled by the run type detailed in Secunda et al. 2025. The differences between the different runs comes from the way the X-ray light curve injected into the simulation is modeled:

Fiducial - X-ray light curve is modeled as a damped random walk with a damping timescale of 30 days
Low Flux - X-ray light curve is modeled as a damped random walk with a damping timescale of 30 days but only 1/4 of the flux injected in the Fiducial run is injected into this simulation
Power-Law - X-ray light curve is modeled using a power-law PSD that goes as the frequency, f^-2
Shallow Power-Law - X-ray light curve is modeled using a power-law PSD that goes as the frequency, f^-1.5
Grey - No injected X-rays in this simulation. The grey UV light curve contains only intrinsic variability driven by disk fluctuations.

Please contact asecunda@flatironinstitute.org with any questions and cite Secunda, A., Jiang, Y.-F., & Greene, J. E. 2025, arXiv:2501.06304.
