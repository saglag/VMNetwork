# VMNetwork
All files are read into Matlab using var = csvread('filename.csv', 1, 1);

DIV dependent recordings:
Branches per day are separated into two results files. 
Results_pt1.csv is always the baseline of the recording and Results_pt2.csv is always the methamphetamine exposure portion. 
Files can be directly concatenated in Matlab as the signal is continuous between condition.

D2 dependency recordings:
All files in D2 branch are full recordings with first half serving as the baseline.
10 uM METH 5uM sulp 2 min base are 10 uM METH co-administered with 5 uM sulpiride (D2 receptor antagonist).
VEH no ANT files are vehicle controls, or recordings only in the presence of ACSF for its entirety.

