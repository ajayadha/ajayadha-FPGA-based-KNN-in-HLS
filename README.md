# KNN-on-ZYBO
To Execute HLS code 
Open HLS folder

The following files are present
1.knn_8_Unpipelined.cpp
2.knn_8_loopUnrolled.cpp
3.Knn_8_pipelined.cpp
4.knn_16_Unpipelined.cpp
5.knn_16_loopUnrolled.cpp
6.Knn_16_pipelined.cpp
7.functions8.h
8.functions16.h
9.knn_8_tb.cpp
10.knn_16_tb.cpp

To execute KNN for 8 dimensional dataset
Add the file 1/2/3 for respective implementation to sources
Add functions8.h to sources
Add knn_8_tb.cpp to testbench

To execute KNN for 16 dimensional dataset
Add the file 4/5/6 for respective implementation to sources
Add functions16.h to sources
Add knn_16_tb.cpp to testbench
 
Perform C Simulation,Synthesis and Co-Simulation

To execute SDK 
Open SDK Folder
hardware code
Generate bitstream
Export hardware
Create new project with respective hardware platform.
Include hardware code either knn_8_hw_sdk.c or knn_16_hw_sdk.c and dataset16.h or dataset8.h for repective simulation.

To execute SDK software code 
Generate bitstream
Export hardware
Create new project with respective hardware platform.
Include software code either knn_8_sw_sdk.c or knn_16_sw_sdk.c and dataset16.h or dataset8.h for repective simulation.




