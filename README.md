# RadiationReport
RadiationReport is Java code to calculate energies, intensities and doses of all radiations as well as logft values for a decay dataset. It is an alternative to the RADLIST and LOGFT Fortran codes combined. It can calculate logft values for forbidden-unique decays with order>2 which are calculated incorrectly as allowed 
decays by the legacy LOGFT code. RadiationReport is part of the [ENSDF Analysis and Utility Programs](https://nds.iaea.org/public/ensdf_pgm/).

Please address any feedback to Jun Chen chenj@frib.msu.edu

## Change history

#### 2024-03
Bug fixes

#### 2023-05
Bug fixes

#### 2023-03
Bug fix: fix incorrect calculations of energies and intensities of Internal Bremsstrahlung spectrum 

#### 2022-12
Improvments in dealing with non-numerical uncertainties 

#### 2022-11
Bug fix: IE is missing in the output file from logft calculations where TI is available with B+ not energetically allowed 

#### 2022-08
Beta version 

## Disclaimer

Neither the author nor anybody else makes any warranty, express or implied, or assumes any legal liability or responsibility for the accuracy, completeness or usefulness of any information disclosed, or represents that its use would not infringe privately owned rights.

