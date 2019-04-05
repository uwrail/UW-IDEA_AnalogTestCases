===============================================
A 12-bit Segmented SAR ADC in TSMC 65nm LP CMOS
===============================================


The provided IP of a12-bit SAR ADC is presented by both cdl netlist and the pdf print of the hierarchical schematics. Users need the following tools, libraries, and agreement to import the cdl netlist and view the original design. If you do not have all of the following requirements. You can still view the design through the pdf print of the hierarchical schematics.

- Tool: Cadence IC616 or later version
- Libraries: analogLib, basic, cdsDefTechLib, functional, US_8ths, tsmcN65
- Agreement: Signed Non-Disclosure Agreement (NDA) between users and TSMC

The testbench for top level is provided, which uses ADE and Spectre. The setup for ADE is provided in the “Simulation Setup and Results.rst”. The hierarchical schematics are listed in Table 1.

.. image :: ./table1.png
     :align: center
     :width: 600
