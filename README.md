Quartus Standard example design demonstrating how to regenerate/update all IP associated with the design prior to compilation.

To compile the design run the following command from the command prompt:

%> quartus_sh -t build_proj.tcl

The build_proj.tcl script sources the quartus_std_ip_update.tcl script which will regenerate/update all of the IP associated with the project prior to building it.
