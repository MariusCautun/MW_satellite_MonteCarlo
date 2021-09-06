# MW_satellite_MonteCarlo  

Code for generating Monte Carlo (MC) samples of the positions and velocities of the Milky Way (MW) satellites with respect to the Galactic Centre. The MC samples are used to account for the measurement uncertainties in the distance modulus, radial velocity, and proper motion of satellites, as well as in the position and velocity of the Sun with respect to the Galactic Centre.  

The [MW_sats_MC_samples.hdf5](data_output/MW_sats_MC_samples.hdf5) file in the [data_output](data_output) folder contains 1000 MC samples of the MW satellites found within 300 kpc that have valid 6D data, i.e. both radial velocity and proper motion measurements. These were obtained using the [McConnachie (2012)](http://www.astro.uvic.ca/~alan/Nearby_Dwarf_Database.html) galaxy catalogue and using the Gaia EDR3 proper motions of [McConnachie & Venn (2020)](https://ui.adsabs.harvard.edu/abs/2020RNAAS...4..229M/abstract). The same data is saved as a numpy binary file in [MW_sats_MC_samples.npz](data_output/MW_sats_MC_samples.npz).

The code for generating this data and the description of the various steps necessary to obtain it can be found in the [MW_satellites_MC_errors.ipynb](MW_satellites_MC_errors.ipynb) Jupyter Notebook.

## Contributors
* **Marius Cautun (Leiden University)** 
