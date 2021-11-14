# Introduction

This project is based on FPGA Developer's project [How to accelerate a Python function with PYNQ](https://www.fpgadeveloper.com/2018/03/how-to-accelerate-a-python-function-with-pynq.html/).  

The following modification to the original project: 

- Upgraded the project for PYNQ Version 2.5 using Xilinx Vivado 2019.1
- Updated the Jupyter Notebook to use memory buffers created by `allocate` DMA library.
  - Read The Docs: https://pynq.readthedocs.io/en/v2.5/pynq_libraries/dma.html
- Created a `makefile` similar to the base design in the PYNQ Z1 repository
  - https://github.com/Xilinx/PYNQ/tree/image_v2.5/boards/Pynq-Z1/base

