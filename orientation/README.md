# Orientation

The real data used for the low-noise examples is twenty-four hours of data from IU.ANMO from
2017-08-26.
The original data files are:
  * _IU.ANMO.10.BH1_
  * _IU.ANMO.10.BH2_
  * _IU.ANMO.10.BHZ_

## Rotation (_/rotation_)

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
  
## Orthogonality (_/orthogonality_)

These examples use the clockwise angle between the BH1 (held constant) and the BH2.  The
examples are designed to test both resolution and a wide variety of different cases of non-
orthogonal components.
* 060	* 080	* 085	* 087	* 088	* 089	* 090	* 091	* 092	* 093	* 095	* 100	* 120	* 270
  
## build_orientation_tests.py

This program created the data examples in these tests.