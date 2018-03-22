# QCMD-analysis

This repository contains python jupyter notebook code for analysis of quartz crystal microbalance (QCM) data measured by the SARK-110 antenna analyzer.

First download the "example_impedance_spectra" folder. This folder contains 5 xlsx files with example data.

Download the SARK_QCMD_w_fitting.ipynb python jupyter notbook. In the notebook, change the directory path in the "folder" variable to match the directory of your "example_impedance_spectra" folder, and run the notebook.

For analysis of new data, the parameter guesses and bounds in the 3rd notebook cell should be changed for accurate fitting. Initial guesses and bounds are eplained in the scipy.optimize.curve_fit documentation here:
https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.curve_fit.html

For other questions, contact Eric M. via ResearchGate:
https://www.researchgate.net/profile/Eric_Muckley
