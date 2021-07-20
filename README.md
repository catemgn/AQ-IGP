# AQ-IGP
WRF-Chem model setup & code for analysis of research paper:

 *Mogno, C., Palmer, P. I., Knote, C., Yao, F., and Wallington, T. J.: Seasonal distribution and drivers of surface fine particulate matter and organic aerosol over the Indo-Gangetic Plain, Atmos. Chem. Phys., 21, 10881–10909, https://doi.org/10.5194/acp-21-10881-2021, 2021.*

The repository includes:
    
#### wrfchem_setup
 - model setup: WRF-Chem namelist.wps and namelist.input, and instructions for code changes (perturbation of bio emissions).
    
#### analysis
 - **clean_observations** : scripts for processing of raw ground-based observations data to be compared with model outputs.
 - **emissions**: scripts for emissions analysis and emissions perturbation over the IGP.
 - **meteo**: scripts for analysisng modeled meteorological varaibles over the IGP.
 - **model_evaluation**: scripts for comapring model outputs with ground based obsevations, literature data and AOD.
 - **PM25_OA**: scripts for analysis of modeled PM2.5 and OA seasonal distribution, composition and sensitivity to emissions.





### License
This code is licensed under the GPLv3.0 License.

[![DOI](https://zenodo.org/badge/327905636.svg)](https://zenodo.org/badge/latestdoi/327905636)
