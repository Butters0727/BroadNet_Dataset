# BroadNet_Dataset

Dataset for series ac arc fault detection. 

__Thesis title:__  
_BroadNet: A Novel Broad Learning System Based Series AC Arc Fault Detection Approach with Time and Frequency Features_

This dataset contains 4000 training samples and 1000 testing samples.

In __train_x__ and __test_x__, each column represents one kind of feature，in the order of variance, stagnation time, integral, mean square, fundamental frequency and  he third harmonic frequency component.

In __train_x__ and __train_y__, every 500 rows represent one kind of state of one appliance, in __test_x__ and __test_y__, every 125 rows represent one kind of state of one appliance, in the order of OMF(N), OMF(A), EHC(N), EHC(A), CPS(N), CPS(A), CW(N), CW(A).

Outdoor motor fan = OMF  
Electric heating cable = EHC  
Compressor = CPS  
Connecting wire = CW  
Normal = N  
Arcing = A
