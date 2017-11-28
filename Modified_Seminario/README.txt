This folder contains all the scripts and example files you need to parameterise bond and angle terms with the output of a Gaussian calculation.

There are a maximum of 3 input files to the modified_Seminario_method.m script:
1. lig.fchk file - This is the output from a Gaussian calculation 
2. lig.log file - This is the output from a Gaussian calculation 
2. Zmat.z - This file is used for atom names and gives OPLS atom types

Run the script with in the folder Modified_Seminario_Method with:

modified_Seminario_method( '../Benzene/', '../Benzene/', 0.957 );

After you run the script you will then have the following outputs.

Modified_Seminario_Bonds - All bond force constants and bond lengths
Modified_Seminario_Angle - All angle force constants and equilibrium values

Average_Modified_Seminario_Bonds - Average bond force constants and bond lengths for bond class
Average_Modified_Seminario_Angles - Average angle force constants and equilibrium values for angle class

Modified_Scaled_Seminario.sb - The new terms are placed into a .sb file 

A tutorial named `Tutorial_Modified_Seminario_Method.pdf' is included for more information. 

If you use the modified Seminario method in your work, please cite:
"AEA Allen, MC Payne, DJ Cole, J. Chem. Theory Comput. (2017) in press, doi:10.1021/acs.jctc.7b00785"

