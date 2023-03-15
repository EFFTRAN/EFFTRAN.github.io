### Efficiency transfer and true coincidence summing corrections for environmental gamma-ray spectrometry

---
**EFFTRAN** is coded in Fortran 77 and runs on the Windows platform through an MS Excel interface written in Visual Basic for Applications (VBA). It is available free of charge and comes complete with the source code.

The user is expected to be familiar with the efficiency transfer method in gamma-ray spectrometry and the application of true coincidence summing corrections. 

EFFTRAN application is limited to coaxial and planar detectors and to cylindrical samples.

HPGe, NaI, and LaBr3 detectors are supported. Gamma-gamma and gamma-X coincidences are taken into account and the correction factors for gamma rays are provided.

Efficiencies can be read from and written to Genie2k calibration files (.CAL) and GammaVision efficiency files (.EFT), and true coincidence summing correction factors can be exported to Genie2k nuclide libraries (.NLB), Genie2k certificate files (.CFT), and GammaVision nuclide libraries (.Lib).

Install a new version of EFFTRAN cleanly into a new directory and not over an existing version. Then redefine all the materials and all the detector and source models that you are using. We apologise for this inconvenience, but there is no other way of guaranteeing that the new version would work correctly.

EFFTRAN uses an embedded copy of the XCOM package (Berger and Hubbel, 1987) as a source of the cross-section data on photon interactions. The KORDATEN database (Arnold and Sima, 2004) serves as a source of nuclear decay data.

To download a copy of the latest version of EFFTRAN (currently 4.7.1) follow [this link](https://efftran.github.io/EFFTRAN_4.7.1.zip).

### Literature

Andreev, D.S., Erokhina, K.I., Zvonov, V.S., Lemberg, I.Kh. 1972. Consideration of cascade transitions in determining the absolute yield of gamma rays. Instruments and Experimental Techniques 15, 1358 (English translation).

Arnold, D., Sima, O., 2004. Application of GESPECOR software for the calculation of coincidence summing effects in special cases. Applied Radiation and Isotopes 60, 167–172.

Berger, M.J., Hubbell, J.H., 1987. XCOM: Photon Cross Sections on a Personal Computer. NBSIR 87-3597, National Bureau of Standards (former name of NIST), Gaithersburg, MD.

Blauuw, M., Gelsema, S.J. 2003. Cascade summing in gamma-ray spectrometry in Marinelli-beaker geometries: the third efficiency curve. Nuclear Instruments and Methods A 505, 311–315.

Vidmar, T. 2005. EFFTRAN - a Monte Carlo efficiency transfer code for gamma-ray spectrometry. Nuclear Instruments and Methods A 550, 603-608.

Vidmar, T., Likar, A. 2005. Calculation of total efficiencies of extended samples for HPGe detectors. Nuclear Instruments and Methods A 555, 251–254.

Vidmar, T., Korun, M. 2006. Calculation of "LS-curves" for coincidence summing corrections in gamma-ray spectrometry. Nuclear Instruments and Methods A 556, 543-546.

Vidmar, T., Kanisch G., Vidmar, G. 2011. Calculation of true coincidence summing corrections for extended sources with EFFTRAN. Applied Radiation and Isotopes 69, 908-911.

Vidmar, T., Capogni, M., Hult, M., Hurtado, S., Kastlander, J., Lutter, G., Lépy, M-C., Martinkovič, J., Ramebäck, H., Sima, O., Tzika, F., Vidmar, G. 2014. Equivalence of computer codes for calculation of coincidence summing correction factors. Applied Radiation and Isotopes 87, 336-341.

Vidmar, T., Camp, A., Hurtado, S., Jäderström, H., Kastlander, J., Lépy, M-C., Lutter, G., Ramebäck, H., Sima, O., Vargas, A. 2016. Equivalence of computer codes for calculation of coincidence summing correction factors – Part II. Applied Radiation and Isotopes 109, 482-486.

Jonsson, S., Vidmar, T, Ramebäck, H. Implementation of calculation codes in gamma spectrometry for correction of systematic effects. 2015. Journal of Radioanalytical and Nuclear Chemistry 303, 1727-1736.

Jonsson, S., Kastlander, J., Vidmar, T, Ramebäck, H. 2020. Experimental validation of corrections factors for γ–γ and γ–X coincidence summing of 133Ba, 152Eu, and 125Sb in volume sources. Journal of Radioanalytical and Nuclear Chemistry 323, 465-472.
