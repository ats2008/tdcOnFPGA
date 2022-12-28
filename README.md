# tdcOnFPGA

Implementation of tappped delay line TDC on FPGA

[TOC]

## Introduction
A TDC is developed targeting Xilinx-Virtex7 FPGA.

## Setup

Clone the repo
```
git clone git@github.com:PranavGovekar/tdcOnFPGA.git 
```
Rebuild the project
```
cd tdcOnFPGA
vivado -source rebuild.tcl
```

**Updating the rebuild.tcl Script**
 Use the TCL prompt in the Vivado Design Suit.
 ```
 write_project_tcl rebuild.tcl -force
 ```
