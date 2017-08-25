## List of Files


00_EHZ.512.seed
... 200 sps calibration output

CB_BC0.512.seed
... 200 sps calibration input

High_Frq_Randomized_calibration_IU_MAJO_00_EHZ_2017.213_majoRESP.pdf
... output of calibration processing using the MAJO/00 response file as input.

High_Frq_Randomized_calibration_IU_MAJO_00_EHZ_2017.213_nrlRESP.pdf
... output of calibration processing using the nrl response file as input.

RESP.IU.MAJO.00.BHZ
... MAJO response file

STS-1_Q330HR_BH_20
... NRL response file

test_results/
... other plots from the Sensor Test Suite

## Processing steps
1. User loads data.  The input channel (CB_BC0.512.seed) is loaded into the top.  No response information is needed.  The output channel is loaded in the bottom with the response information.

2. User zooms in on data.  Before and after the calibration signal there is some amount of data that is not needed.  It is standard practice to zoom in on just the portion of the data that contains the signal.

3. Generate result by hitting the result button. Make sure to uncheck the LF calibration box.

4. The result will show a blue line that shows the cross-PSD of the calibration input and output, a red line that shows the input response and a green line that shows the fit of the data.  A box in the corner will show the initial poles and the fit poles.

5. Generate report.  Hitting this button will produce a detailed result like the ones listed above.

