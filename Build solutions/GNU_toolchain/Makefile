#Makefile of module_name
  #author:Vdragon(pika1021@gmail.com)
  #this file is licensed under LGPL 3 or later
MODULE_NAME = module_name
build:
	mkdir --parents Simulation
	iverilog \
		-o ../GNU_toolchain/Simulation/${MODULE_NAME}_testbench.executable \
		../Source_code/${MODULE_NAME}_testbench.v

simulate:
	Simulation/${MODULE_NAME}_testbench.executable

viewWaveform:
	gtkwave Simulation/${MODULE_NAME}_testbench.vcd &
