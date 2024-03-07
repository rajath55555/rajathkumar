# FUNCTIONAL SIMULATION
**For Ubuntu**

 Open your terminal and type the following to install iverilog and GTKWave
 ```
 $   sudo apt get update
 $   sudo apt get install iverilog gtkwave
 ```

![11](https://github.com/rajath55555/rajathkumar/assets/119932039/242b160e-6090-4717-9309-efc32323ac87)


- **To clone the repository and download the netlist files for simulation, enter the following commands in your terminal.**

 ```
 $ git clone https://github.com/rajath55555/rajathkumar.git
 $ cd Documents
 $ cd hello
```

![22](https://github.com/rajath55555/rajathkumar/assets/119932039/b29c533c-9a6d-4292-984d-f678acd3fe63)



- **To simulate and run the Verilog code, enter the following commands in your terminal.**

```
$ iverilog -o hello hello.v hello_tb.v
$ ./hello
```

![33](https://github.com/rajath55555/rajathkumar/assets/119932039/392a5413-a6a6-4eef-8e17-b7f9cea77933)


- **To see the output waveform in gtkwave, enter the following commands in your terminal.**

`$ gtkwave hello.vcd`



  Full 5-stage instruction pipeline and pc-increment description Waveform
  

![44](https://github.com/rajath55555/rajathkumar/assets/119932039/b775e1fb-234b-41c0-83bd-b5ffbb768601)
![55](https://github.com/rajath55555/rajathkumar/assets/119932039/fb1d6a2f-424d-45fd-8704-d02646afd04d)
