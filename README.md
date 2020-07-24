# random_mt_scripts

Some scripts I use in MT data processing and modeling. I hope these could be useful for other people as well.
Most of them are spaghetti codes written in python but they are working. Do not expect elegance :P. Most of them
uses Python2 rather than 3.

***MT_MESH***

It has to be run in the same directory with the edi files. Should read most edi files, but may fail with some.

MODEM initial file creation program.
Can do:
-Use topography xyz file to add sea cells.
-Use topography xyz file to add topography to the model.
-Use another resistivity model to create a different one with different geometry.

***SENSE_WS***

Run it in the same folder with the rho, dat files (ModEM).

Edit existing rho files with the assist of indexed plots. 
Could be used for making sensitivity tests

***avg_edi***


It has to be run in the same directory with the edi files. 

Returns average, median and resistivity distribution for the
selected frequency range.

***conf_waldim***

It has to be run in the same directory with the edi files.

Creates waldim input files.

***create_OCCAM1D_files***

It has to be run in the same directory with the edi files.

creates OCCAM1D files from an edi

***egbert2edi***

Convert the format output of the data processing code of Egbert (1997)

***fit_mod***

Plots the curve fittings of outputs of modem dat files.
Dat files has to be in the directory.

It has to be run in the same directory with the dat files.
The firs file in the alphabetical order is going to be the data dat file. So change its name to 0.dat or something.

***frek***

Excludes data from edi files by input interface where the user enter the index of the frequencies.
response_mtcheck can be used to plot the edi files first to which indexes are going to be kept.

It has to be run in the same directory with the edi files.

***j2edi***

conversion from j file format to edi format.

***plot_modem_slice***

quick and easy depth-slice plotting tool without going into paraview or something.

***plot_rose***

plots rose diagram of the selected edi files and frequencies.
Also plots pt beta histograms.

It has to be run in the same directory with the edi files.

***response_mtcheck***

plots edi files for all components and phase tensor elements.

***rho2ws***

ModEM format to WS3DINV format conversion


***rms_map***

calculates local rms values of modem dat files.

***rms_diff_map***

calculates local differences in rms values between different dat files.


