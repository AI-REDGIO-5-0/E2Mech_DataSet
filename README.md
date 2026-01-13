# E2Mech_DataSets

This repo contains files related to vibration signals collected during our (DFII, E2Mech) experiment. Specifically the benchmark system (a flexible Stephenson's mechanism)
has been run at different speed and vibration data have been collected by means of sensorboards. 

1st Iteration Dataset:
 Healthy and Faulty scenarions have been reproduced considering different settings of the control algorithm steering the system.

 In the following we provide the legend to interpret data:

 File names:
  - File name is Vib_<Speed in rpm>_<axis of acceleration> to indicate healthy scenario data
  - For faulty data the nomenclature is enriched as Vib_<Speed in rpm>_<axis of acceleration>_Faulty

 File content:
 - Each csv file contains n columns, corresponding to n windows cut from the acquisition, the number of rows correspond to the samples per window
 - The sampling frequnecy of the accelerations is Fs= 27KHz
 - g units have been used to represent the acceleration measurements

2nd Iteration Dataset:

In this case healthy and faulty scenarios have been obtained considering the flexible mechanism running alone (healthy) at a constant speed of 300rpm, and adding a perturbation from the activation, with a small 10 degrees movement, of another (rigid) mechanism close to the flexible one for reproducing a "faulty" condition (which changes slightly the vibration pattern).

Folder names: 
 2ndIteration_Healthy_Data: Contains a collection of .parquet files with the timestamp and the raw vibration signals collected from the sensorboards during the healthy   scenario
 
 2ndIteration_Faulty_Data: Contains a collection of .parquet files with the timestamp and the raw vibration signals collected from the sensorboards during the faulty   scenario

 Folder content: 
 Each folder contains a set of .parquet files with: timestamp, and raw acceleration measurements, sampled at 27KHz and expressed in g units, gathered from the sensorboard.
 
- File name is

