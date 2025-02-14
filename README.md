# HextechArchitecture
> Pipelined Processor inspired by ARMv7 Architecture

You need to install [Icarus Verilog](https://bleyer.org/icarus/), [GTKWave](https://gtkwave.sourceforge.net/) and [Make](https://www.gnu.org/software/make/manual/make.html). 

### For Apple Silicon (M1/M2/M3/M4):

You need to install [Homebrew](https://brew.sh/)

To install Icarus Verilog:
```bash
brew install icarus-verilog
```

To install GTKWave:
```bash
brew install --HEAD randomplum/gtkwave/gtkwave
```

To install Make:
```bash
brew install make
```

### Run the project:

To run the project, you need to be inside the HexCore folder. 

Use this commant to build the `prossesor.out` file:
```bash
make
```

Use this command to run the simulation and view the waveforms:
```bash
make sim
```

Use this command to delete the files generated after the simulation:
```bash
make clear
```