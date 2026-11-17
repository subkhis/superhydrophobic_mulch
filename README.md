# superhydrophobic_mulch
This repository contains experimental data and Mathematica notebook files related to paper titled "Quantifying Steady State Evaporation Fluxes from Saturated and Unsaturated Sandy Soils Mulched with Superhydrophobic Sand: Experiment and Theory"

Experimental_data_all.xlsx contains all the experimental data presented in the manuscript.

data_analysis.nb is a Mathematica notebook file to analyze the experimental and simulation data and to produce figures in the manuscript. Some data need to be imported from:
fine_soil_log.dat
coarse_soil_log.dat
fs00_Tprofile_t48hrs.dat
fs05_Tprofile_t48hrs.dat
fs10_Tprofile_t48hrs.dat
cs00_Tprofile_t48hrs.dat
cs05_Tprofile_t48hrs.dat
cs10_Tprofile_t48hrs.dat

column_evaporation_solver_with_sand_mulch_hourly.nb is a Mathematica notebook file to run heat transfer simulation to produce soil column temperature profile

particle_size_analysis.nb is a Mathematica notebook file to analyze particle size distribution. Using the sieve values, the mean particle size and the standard deviation can be obtained.

unsaturated_soil_model.nb is a Mathematica notebook file for fitting the experimental data of evaporative flux with the proposed model presented in the manuscript.

The code for image analysis can be obtained from this link: https://github.com/jiaqizheng2000/Image_analysis-main
