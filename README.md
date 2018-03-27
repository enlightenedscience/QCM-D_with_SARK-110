# QCMD-analysis

This repository contains python jupyter notebook code for analysis of quartz crystal microbalance (QCM) data measured by the SARK-110 antenna analyzer (http://www.sark110.com/).

First download the "example_impedance_spectra" folder. This folder contains 5 xlsx files with example data.

Download the SARK_QCMD_w_fitting.ipynb python jupyter notbook. In the 5th cell in the notebook, change the directory path in the "folder" variable to match the directory of your "example_impedance_spectra" folder, and run the notebook.

For analysis of new data, the parameter guesses and bounds in the 4th notebook cell should be changed to improve the fitting accuracy. Initial guesses and bounds are explained in the scipy.optimize.curve_fit documentation here:
https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.curve_fit.html


The repository also contains files for a 3D-printed flow cell with gas inlet/outlet ports and slots for three BNC connector feedthroughs. The top and bottom pieces of the flow cell are "Environmental box CNMS top.stl" and "Environmental box CNMS bottom.stl". 



For questions, contact Eric M. via ResearchGate: https://www.researchgate.net/profile/Eric_Muckley
