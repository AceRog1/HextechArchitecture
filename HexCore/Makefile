OUT = prossesor.out
SRC = $(wildcard design/*.v) testbench/pipelined_tb.v
SIM = waveforms.vcd

all: 
	iverilog -o $(OUT) $(SRC)

sim:
	vvp -n $(OUT) && gtkwave $(SIM)

clear:
	rm -f $(OUT) $(SIM)