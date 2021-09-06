# MW_satellite_MonteCarlo  

Code for generating Monte Carlo (MC) samples of the positions and velocities of the Milky Way (MW) satellites with respect to the Galactic Centre. The MC samples are used to account for the measurement uncertainties in the distance modulus, radial velocity, and proper motion of satellites, as well as in the position and velocity of the Sun with respect to the Galactic Centre.  

The ['data_output'](data_output) folder contains 1000 MC samples of the MW satellites found within 300 kpc that have valid 6D data, i.e. both radial and proper motion measurements. There were obtained using the [McConnachie (2012)]() galaxy catalogue and using the Gaia EDR3 proper motions of [McConnachie & Venn (2020)]().  

The code for generating this data and the description of the various steps cessary to obtain it can be found in the [MW_satellites_MC_errors.ipynb](MW_satellites_MC_errors.ipynb) jupyter notebook.

## Contributors
* **Marius Cautun (Leiden University)** 
