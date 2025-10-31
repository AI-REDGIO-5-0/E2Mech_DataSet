# E2Mech_DataSet

This repo contains files related to vibration signals collected during our (DFII, E2Mech) experiment. Specifically the benchmark system (a flexible Stephenson's mechanism)
has been run at different speed and vibration data have been collected by means of sensorboards. Healthy and Faulty scenarions have been reproduced considering different settings of the control algorithm steering the system.

In the following we provide the legend to interpret data:

File names:
  - File name is Vib_<Speed in rpm>_<axis of acceleration> to indicate healthy scenario data
  - For faulty data the nomenclature is enriched as Vib_<Speed in rpm>_<axis of acceleration>_Faulty

File content:
- Each csv file contains n columns, corresponding to n windows cut from the acquisition, the number of rows correspond to the samples per window
- The sampling frequnecy of the accelerations is Fs= 27KHz
- g units have been used to represent the acceleration measurements
