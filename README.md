# DataCode_LS4P-I
Here are stored the evaluation data and model data used in the paper "Impact of Initialized Land Surface Temperature and Snowpack on Subseasonal to Seasonal Prediction Project, Phase I (LS4P-I): Organization and Experimental design" by Xue and co-authors submitted to Geoscientific Model Development (GMD) for publication. The Precipitation (pre) is for June while the 2m-temperature (T-2m) in for May. Although all model simulations are available and freely accessible at the TPE data center (see Appendixes B and C for detailed instructions how to access the data), we have shared all the observational data and model outputs utilized in the paper in this link.

A) Under the folder "EvaluationData", the data used for the evaluation of the different Tasks (Task1 and Task2) are included.

1) CMA data is the gauge-based data from the Chinese Meteorological Administration (CMA). Under the folder "CMA" is shared 4 files: CMA_pre.climatology.nc (Precipitation climatology), CMA_t2m.climatology.nc (2m-temperature climatology),CMA_pre.june.2003.nc (June 2003 precipitation), and CMA_t2m.may.2003.nc (May 2003 2m-temperature).

2) CRU is the global time-series from the Climate Research Unit at the University of East Anglia. Under the folder "CRU" is shared two files: CRU_pre.climatology.nc (precipitation climatology) and CRU_pre.june.2003.nc (June 2003 precipitation).

3) CAMS data is collected from the Global Historical Climatology Network version 2 and the Climate Anomaly Monitoring System (GHCN + CAMS). Under the folder "CAMS" is shared two files: CAMS_t2m.climatology.nc (2m-temperature climatology) and CAMS_t2m.may.2003.nc (May 2003 2m-temperature).

For the climatology, the 1981-2010 period is used. The CMA data is used over the China, while CAMS (CRU) are used elsewhere for 2m-Temperature (precipitation). We have also provided an example of script ("atribex.gs") used to generate the T-2m composite anomaly for the evaluation (see EastAsia_OBS_anoTMPsfc.png the figure generated). Please note this  script could be used for the corresponding precipitation anomaly composite also (after change variable T-2m to Pre).

B) Under the folder “ModelOutputs”, the simulation ensemble mean for Task1 and Task2 for both precipitation and 2m-temperature, which are used for Figures 6 and 7, are stored. 

1) "EnsMean_LS4P_pre.nc" has the precipitation and containts five variables: obs2003 (June 2003 Obs), ens2003 (ensemble mean Task1), ensclim (ensemble mean Task2), ensbias2003 (Task1 bias), and ensbiasclim (Task2 bias).

2) "EnsMean_LS4P_t2m.nc" has the 2m-temperature and containts five variables: obs2003 (May 2003 Obs), ens2003 (ensemble mean Task1), ensclim (ensemble mean Task2), ensbias2003 (Task1 bias), and ensbiasclim (Task2 bias).

Note 1: Precipitation unit: mm/day; 2m-Temperature unit: K

Note 2: The precipitation data are for the month of June, while the 2m-temperature are for May.
 

