
Xilinx Toolchain
===================

Chapter Two of "FPGAs!? Now What?" gives a good overview of the full
compilation process. The basic layers are:

**Synthesis**
    The "logic synthesizer" compiles from HDL to a netlist

**Implementation**
    The "translator" takes a set of netlists and design constraints and generates
    a merged netlist.

    Then a "mapper" regroups the netlist so that place and route will be easier

    Then a "place and route" tool decides exactly how the FPGA logic will be
    configured

**Bitstream**
    The "bitstream generator" translates the configuration into the binary
    format that the FPGA uses to re-flash itself

File Extensions
-------------------

.. include:: xilinx_filetypes_table.txt


See also:

- https://github.com/JPNaude/X-MimeTypes/blob/master/eda_mime_types.xml
- http://www.xilinx.com/support/documentation/sw_manuals/xilinx14_4/cgn_r_core_generator_output_files.htm
- http://www.xilinx.com/support/documentation/sw_manuals/xilinx14_4/ise_r_source_types.htm
- devref.pdf (UG628)

