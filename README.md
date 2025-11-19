# FPGA
it is a self-note of a embedded SW dev to get a foot in FPGA field

# https://www.youtube.com/watch?v=B-CbDfrfJRk&list=PLXSyc11qLa1ZutrEG2XmyWrNz17SSQTdH

Zynq Part 1
# HW architect
Zynq SoC: processing unit (APU: application proxcessing unit) + PL (FPGA)
ddr RAM
qspi: fpga
fmmc: sd card

reconfigure zynq SoC
FTDI: USB - JTAG,  USB - UART converter

1st step --> check voltage on board

# vivado: (free)
1. create new blank project --> select right IC
2. check jtag connection <-- remove power <-- make sure boot mode is setting correctly (jtag need to be in cascade mode)
3. we will see 2 arm cores
4. Next we need to check read and write to memory: use cmd to write to an memory address.
5. Run hello world: add zync chip on vivado, connect them

Conclusion: seems like FPGA is kinda different with what I am doing currently --> switch scope to embedded AI may have more potential
