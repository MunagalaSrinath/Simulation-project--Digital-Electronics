# TITTLE
DESIGN AND SIMULATE 6 BIT BINARY TO GREY CONVERTER USING VERILOG

# THEORY

# LOGIC DIAGRAM

# NETLIST DIAGRAM
![image](https://github.com/MunagalaSrinath/Simulation-project--Digital-Electronics/assets/118678482/920a998b-37d7-4611-abc6-f7615f775590)


# TIMING DIAGRAM
![image](https://github.com/MunagalaSrinath/Simulation-project--Digital-Electronics/assets/118678482/b536d6c2-a8ef-4a89-b5ef-8db45ae1ac38)


# PROGRAM
```
module ddd (
    input [5:0] binary,
    output [5:0] gray
);

    assign gray[0] = binary[0];
    assign gray[1] = binary[1] ^ binary[0];
    assign gray[2] = binary[2] ^ binary[1];
    assign gray[3] = binary[3] ^ binary[2];
    assign gray[4] = binary[4] ^ binary[3];
    assign gray[5] = binary[5] ^ binary[4];

endmodule
```


# REFERENCE
