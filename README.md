# JBC-STORM-2020
STORM localization files, Clus-DoC output, and scripts

Data is found in the ___________ directory


Scripts (MATLAB 2018a) used to extract the data we used to generate figures is found in the Scripts directory.

To use the scripts, the files (for 2-color data) are specified at the top. The computed averages are output to the Command Window when run. To run the script for different cluster interaction types, find the commented section between lines 126 and 144, and between lines 181 and 199. Comment-out the sections that don't apply and un-comment the section you want to use. Each discards the clusters that don't match the desired number of constituents (Nb) and number of interactions (Nb_In). If no clusters are found for the given thresholds, it will report data on the number of interacting molecules for each channel and the fraction of them interacting. Please see ClusDoC documentation for the units and meaning of the output values. The output may be pasted into Excel with Paste Special to format the data into different cells.