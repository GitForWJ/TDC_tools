# TDC_tool

This repository is for the article entitled "128-channel high-linearity resolution-adjustable time-to-digital converters for LiDAR applications: software predictions and hardware implementations"

Authors: Wujun Xie, Yu Wang, Haochang Chen and David Day-Uei Li.

The tool is developed by Wujun Xie.

This tool is developed on MATLAB. The MATLAB Runtime version 9.1 (R2016) is needed.

1. Select the tested device and the target channel first.

2. Check the length of the TDL before setting the Start-point and the end-point. The built-in TDLs are from Bin 1 to Bin 460.

3. Run the code density test first before running the time interval test.

4. Jitters from the delay element, the input signal and the clock source can be modified. The default values are from our previous test results.

**Note:** Users can upload their original TDL data (code density test results,.mat file only) to the tool. The data should be named as "unnamed1" and stored in two columns; columns 1 is for count times and columns 2 is the corresponding address. An example is given, see Ch_example.mat.