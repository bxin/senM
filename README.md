# ZEMAX and FEMAP
This repository keeps track of the files generated by ZEMAX and FEMAP/NASTRAN analysis

bendingModeGridFiles/

*  120 DAT files =   3 (M1, M3, M2) x 20 (modes) x 2 (+ and -)

*  80 gridz files =   2 (M13, M2) x 20 (modes) x 2 (+ and -)

ZEMAX/LSSTv33_1c1w_As_CornerNoComp_x3_gridSag.zmx

* Zemax file (v3.3, modified to g-band, 500nm only, multi-config for 1.5mm, -1.5mm, and in focus); match to ZEMAX/ZernikeAnnularCoeff.txt before use.

ZEMAX/LSSTv33_1c1w_As_CornerNoComp_x3_gridSag.CFG

*. config file for the above ZEMAX file

ZEMAX/ZernikeAnnularCoeff.txt

* Zernike Annular Coefficients for 500nm g-band design. Used for verifying the Zemax model has been configured correctly.

perturbedZernikes/comcam/

* 101 files = 50 (DOFs) x 2 (+ and -) + intrinsic

* each file has 9 rows, for 9 fields, and 24 columns, for z1-z22 then residual RMS and PV RMS

perturbedZernikes/senM35/

* 101 files = 50 (DOFs) x 2 (+ and -) + intrinsic

* each file has 35 rows, for 9 fields, and 24 columns, for z1-z22 then residual RMS and PV RMS

perturbedZernikes/senM189/

* 101 files = 50 (DOFs) x 2 (+ and -) + intrinsic

* each file has 189 rows, for 9 fields, and 24 columns, for z1-z22 then residual RMS and PV RMS

intrinsicByBand/comcam/

* intrinsic aberrations for comcam (9 fields), by band, at its effective wavelength (as defined in LSE-40)

intrinsicByBand/lsst/

* intrinsic aberrations for lsst (35 fields), by band, at its effective wavelength (as defined in LSE-40)

intrinsicByBand/lsstfam/

* intrinsic aberrations for lsstfam (189 fields), by band, at its effective wavelength (as defined in LSE-40)


