# EFFTRAN.github.io

## Efficiency transfer and true coincidence summing corrections for gamma-ray spectrometry

The code is written in Fortran 77 and runs on the Windows platform through a GUI written in Visual Basic. EFFTRAN is available free of charge. To get a copy, please write to tim.vidmar@sckcen.be. 

The user is expected to be familiar with the efficiency transfer method in gamma-ray spectrometry and the application of true coincidence summing corrections. 

EFFTRAN application is limited to cylindrical detectors and samples and to axially symmetric setups. HPGe, NaI, LaBr3, CZT and CLYC detectors are supported. Gamma-gamma and gamma-X coincidences are taken into account and the correction factors for gamma rays are provided.

Import and export of efficiencies to GENIE calibration files (.CAL) and GammaVision efficiency files (.EFT) is possible, as well as import and export of true coincidence summing correction factors to GENIE nuclide libraries (.NLB) and certificate files (.CFT), and to GammaVision nuclide libraries (.Lib).

When installing a new version of EFFTRAN, install it cleanly into a new directory and not over an existing version. Then redefine all the materials and all the detector and source models that you are using. We apologies for this inconvenience, but there is no other way of guaranteeing that the new version would work correctly.

EFFTRAN uses and embedded copy of the XCOM package (Berger and Hubbel, 1987) as a source of the cross-section data on photon interactions. The KORDATEN database (Arnold and Sima, 2004) serves as a source of nuclear decay data.

### Literature

Andreev, D.S., Erokhina, K.I., Zvonov, V.S., Lemberg, I.Kh. 1972. Consideration of cascade transitions in determining the absolute yield of gamma rays. Instruments and Experimental Techniques 15, 1358 (English translation).

Arnold, D. and Sima, O., 2004. Application of GESPECOR software for the calculation of coincidence summing effects in special cases. Applied Radiation and Isotopes 60, 167–172.

Berger, M.J. and Hubbell, J.H., 1987. XCOM: Photon Cross Sections on a Personal Computer. NBSIR 87-3597, National Bureau of Standards (former name of NIST), Gaithersburg, MD.

Blauuw, M., Gelsema, S.J. 2003. Cascade summing in gamma-ray spectrometry in Marinelli-beaker geometries: the third efficiency curve. Nuclear Instruments and Methods A 505, 311–315.

Vidmar, T. 2005. EFFTRAN - a Monte Carlo efficiency transfer code for gamma-ray spectrometry. Nuclear Instruments and Methods A 550, 603-608.

Vidmar, T., Likar, A. 2005. Calculation of total efficiencies of extended samples for HPGe detectors. Nuclear Instruments and Methods A 555, 251–254.

Vidmar, T., Korun, M. 2006. Calculation of "LS-curves" for coincidence summing corrections in gamma-ray spectrometry. Nuclear Instruments and Methods A 556, 543-546.

Vidmar, T., Kanisch G., Vidmar, G. 2011. Calculation of true coincidence summing corrections for extended sources with EFFTRAN. Applied Radiation and Isotopes 69, 908-911.

T. Vidmar, M. Capogni, M. Hult, S. Hurtado, J. Kastlander, G. Lutter, M.-C. Lépy, J. Martinkovič, H. Ramebäck, O. Sima, F. Tzika, G. Vidmar. 2014. Equivalence of computer codes for calculation of coincidence summing correction factors. Applied Radiation and Isotopes 87, 336-341.

T. Vidmar, A. Camp, S. Hurtado, H. Jäderström, J. Kastlander, M-C. Lépy, G. Lutter, H. Ramebäck, O. Sima, A. Vargas. 2016. Equivalence of computer codes for calculation of coincidence summing correction factors – Part II. Applied Radiation and Isotopes 109, 482-486.

