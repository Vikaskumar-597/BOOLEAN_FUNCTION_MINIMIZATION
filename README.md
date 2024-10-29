# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**


![WhatsApp Image 2024-10-29 at 10 50 34_a644ceec](https://github.com/user-attachments/assets/69d39b15-6da9-429b-ab89-5162f1e585f8)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module exp2(f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor,a,b);
input a,b;
output f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor;
and (f_and,a,b);
or (f_or,a,b);
not (f_not,a);
nor (f_nor,a,b);
nand (f_nand,a,b);
xor (f_xor,a,b);
xnor (f_xnor,a,b);
endmodule
```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by  : Vikaskumar M
   RegisterNumber: 24900247


**RTL realization**
![exp2](https://github.com/user-attachments/assets/24dcf3b7-1ccf-4e26-82a4-0aa190ae8151)


**Timing Diagram**
![Screenshot 2024-10-20 180355](https://github.com/user-attachments/assets/d2913aac-ae78-477d-a840-8b6987d68521)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

