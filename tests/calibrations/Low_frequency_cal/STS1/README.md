## List of Files

oldASL_method/
... directory containing results from the previous method of ASL long-period corner frequencies

00_BHZ.512.seed
... 20 sps calibration output

BC0.512.seed
... 20 sps calibration input

Low_Frq_Randomized_calibration_IU_MAJO_00_BHZ_2017.213_MAJOResp.pdf
... output of calibration processing using the MAJO/00 response file as input

Low_Frq_Randomized_calibration_IU_MAJO_00_BHZ_2017.213_nrlResp.pdf
... output of calibration processing using the nrl response file as input

RESP.IU.MAJO.00.BHZ
... MAJO response file

STS-1_Q330HR_BH_20
... NRL response file

test_results/
... other plots from the Sensor Test Suite


## Processing steps
1. User loads data.  The input channel (BC0.512.seed) is loaded into the top.  No response information is needed.  The output channel is loaded in the bottom with the response information.

2. User zooms in on data.  Before and after the calibration signal there is some amount of data that is not needed.  It is standard practice to zoom in on just the portion of the data that contains the signal. For the long period data it may be necessary to cat the seed files from 2 days together.

3. Generate result by hitting the result button. Make sure the LF calibration box is checked.

4. The result will show a blue line that shows the cross-PSD of the calibration input and output, a red line that shows the input response and a green line that shows the fit of the data.  A box in the corner will show the initial poles and the fit poles.

5. Generate report.  Hitting this button will produce a detailed result like the ones listed above.

