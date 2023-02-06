# Lab 1 - GHDL and GTKWave

 Installation was straightforward, as the instructions were specific and clear. After installing GHDL and GTKWave, I ran the following commands:
```
$ ghdl -a ha.vhdl
$ ghdl -a ha_tb.vhdl
$ ghdl -e ha_tb
$ ghdl -r ha_tb --vcd=ha.vcd
ha_tb.vhdl:47:5:@5ns:(assertion error): Reached end of test
$ gtkwave ha.vcd
```
These commands ran the Half Adder example and produced this output:

![Half Adder example program output](https://github.com/aguadagn/2023S-EE-322-A/blob/main/Lab_01/half%20adder%20example.png)

After the first example was documented, I ran these commands in order to run the 4-to-1 multiplexer example:
```
$ ghdl -a mux.vhdl
$ ghdl -a mux_tb.vhdl
$ ghdl -e mux_tb
$ ghdl -r mux_tb --vcd=mux.vcd
$ gtkwave mux.vcd
```
The 4-to-1 Multiplexer program produced this output:

![4-to-1 Multiplexer program output](https://github.com/aguadagn/2023S-EE-322-A/blob/main/Lab_01/4%20to%201%20multiplexer.png)

Overall, GTKWave not extremely difficult to use, and the example programs given were interesting.
