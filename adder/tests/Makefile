

TOPLEVEL_LANG ?= verilog

PWD=$(shell pwd)

export PYTHONPATH := $(PWD)/../model:$(PYTHONPATH)

    VERILOG_SOURCES = $(PWD)/../hdl/adder.sv

GUI=1
TOPLEVEL := adder
MODULE   := test_adder

include $(shell cocotb-config --makefiles)/Makefile.sim
