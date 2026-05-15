# BREAD_DAQ
Code to pull data from the Xilinx board of the Harvard-based BREAD experiment, average over time, and characterize the resulting data.

Note all the below .ipynb in this repo must be run on a Xilinx FPGA board with QUIK infrastructure and an image already loaded on it. All cells in both notebooks are completely independent, designed to be able to be run in any order or copied into a .py file without issue.

bread_real_firmware.ipynb is the Python code to pull through the Verilog firmware and retrieve data at different stages of the digital logic acquisition chain

characterization.ipynb contains code to average noise down and save the data for analysis of axion-finding projections and statistical analyses

averaging_two_nyquist.ipynb contains novel code to average noise over two Nyquist zones at once searching for an axion signal
