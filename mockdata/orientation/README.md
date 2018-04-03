# Orientation

The real data used for the low-noise examples is twenty-four hours of data from IU.ANMO from
2017-08-26.
The original data files are:
  * _IU.ANMO.10.BH1_
  * _IU.ANMO.10.BH2_
  * _IU.ANMO.10.BHZ_
  
The original data files used for the high noise examples are from IU.FUNA from 2017-09-19:
  * _IU.FUNA.00.BH1_
  * _IU.FUNA.00.BH2_
  * _IU.FUNA.00.BHZ_
  
## Rotation (/rotation)

These examples show the data rotated clockwise by the specified number of degrees.  Each 
set is in its own directory indicated by the number of degrees that the signal was rotated.
  * _002_
  *  _005_
  * _020_
  * _090_
  * _110_
  * _180_
  * _200_
  * _270_
  * _290_
  * _355_
  * _358_
  
## Orthogonality (/orthogonality)

These examples use the clockwise angle between the BH1 (held constant) and the BH2.  The
examples are designed to test both resolution and a wide variety of different cases of non-
orthogonal components.
  * _060_	
  * _080_	
  * _085_	
  * _087_	
  * _088_	
  * _089_	
  * _090_	
  * _091_	
  * _092_	
  * _093_	
  * _095_	
  * _100_	
  * _120_	
  * _270_

_Note: we did not create any cases of non-orthogonality to the vertical axis, but this would 
be possible._
  
## build_orientation_tests.py

This program created the data examples in these tests.  The testing of the data for sanity
has not been fully done.