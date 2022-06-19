# Integrated-Circuit-Design-VHDL-LIFO
In the design of the LIFO Buffer testbench, we used the LIFO48 model as a component in
order to simulate the test runs of the LIFO Buffer. In order to map these component values to
the signal values, we use the port map. Since the buffer is a synchronous process, we
simulate the clock positive and negative edges using a process; this is used in unison with
the LIFO48 model to trigger the LIFO_proc process and initiate changes to the values of
Full and Empty.
