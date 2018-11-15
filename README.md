# this is the project to make a single cycle cpu

# how to run the simulation?
```shell
cd testbench/socomp_dataflow_test
iverlog -o soccomp_dataflow.vpp soccomp_dataflow_tb.v
./soccomp_dataflow.vpp
open -a Scansion sccomp_dataflow.vcd
```
> I use `iverlog` to compile the executive file `soccomp_dataflow.vpp`
> And I use the Scansion to analysis the `.vcd` file which generated by the `.vpp`file