# Seismic Test Data

## Description

This data is provided along with code and methods used to generate the data in order to 
provide a test data set.  This data set was originally designed to provide tests and 
verification for 
computational methods used or developed at the Albuquerque Seismological Laboratory.  
These tests ensure that computational methods provide expected results.  

Some of these tests can 
be thought of as unit tests.  However, some test data and results may depend slightly on 
the methods used for calculation and other parameters and as such may not be exactly like 
unit tests.  For example, there are many ways to calculate a PSD and each one will provide 
slightly different results, but the major features of the PSD should remain unchanged, or 
if there is a significant change that behavior should be understood.

This data set tries to provide some test cases using both synthetic and real seismic data. 
Each data test case is broken into a subdirectory and sometimes into a category (directory) 
that contains multiple test cases for that category such as calibration data.

## Organization
* Instrument Correction
* PSD Calculation
  * Synthetic data
  * Low Station Noise
  * High Station Noise
  * Transient Noise
* Orientation
  * Component Rotation (two sensor)
  * Components rotated by known angle 
    * Low-Noise
    * High-Noise
  * Non-orthogonal Components on one sensor
* Relative Gain
* Calibration Processing
  * High-frequency
  * Long-period
* Sensor Self-Noise

## Contact
This effort is being conducted at the U.S. Geological Survey Albuquerque Seismological 
Laboratory.  
Please contact us https://earthquake.usgs.gov/contactus/albuquerque/ for more information.


## Disclaimer

These data and software are preliminary or provisional and are subject to revision. They 
are being provided to meet the need for timely best science. The data and software have not 
received final approval by the U.S. Geological Survey (USGS) and are provided on the 
condition that neither the USGS nor the U.S. Government shall be held liable for any 
damages resulting from the authorized or unauthorized use of the data or software.

