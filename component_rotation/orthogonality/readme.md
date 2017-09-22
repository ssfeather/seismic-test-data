## Description
This directory contains data from an STS-1 on an ASL test system that has the horizontal components set up at a non-orthogonal angle.

## Contents:
orthogonal/
... data and results from XX_STSX before the sensor was moved. data is from 2017.  subdirs are
    named with the DOY that the data comes from.

non-orthogonal/
... data and results from XX_STSX after the sensor was moved. data is from 2017.  subdirs are
    named with the DOY that the data comes from.

reference/
... data from XX_TST1 for reference. data is from 2017.  subdirs are
    named with the DOY that the data comes from.

results/
... images from sensor test suite and azimuth programs showing results of the data

Three results have been produced for this test.  Data from before the sensors were moved, data after the sensors were moved and data after the angle between the sensors was corrected.  The first time the sensors were set at the non-orthogonal angle, there were field deployments using the equipment and it was not as precise as we wanted.  When the digital compass returned to ASL, Kyle Persefield went up to the vault and reoriented the sensors.  He found that he was off by 1.5 degrees.  Processing with the test suite can pick out these small changes in angle. Currently the orientation angle calculation is off by 180.


