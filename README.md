# TDC_tools

This repository is for the article entittled "Multichannel high-linearity resolution-adjustable time-to-digital converters for LiDAR applications: software verifications and hardware implementations"

Authors: Wujun Xie, Haochang Chen and David Day-Uei Li.

The tool is developed by Wujun Xie.

This tool is based on MATLAB. The MATLAB Runtime version 9.1 (R2016) is needed.

1. Select the targe channel and the tested device first.

2. Check the length of the TDL before setting the Start-point and the end-point.

3. Run the code density test first before running the time interval test.

4. Jitters from delay elements and clock sources can be modified. The default values are from our previous test results. 

The TI tests are based on the equations below:

$\sigma_{clk}^2 = \sigma_{clk}^2 + \sigma_{eq}^2 + \sigma_{DL}^2$

$\sigma_{DL}^2 = (n/2)*\sigma_{CY}^2$

$\sigma_{eq}^2 = sum^N_{i=1} \frac{W[i]^3}{12*W_{total}}$