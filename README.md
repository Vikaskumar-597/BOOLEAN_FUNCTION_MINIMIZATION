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
module exp3(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by  : Vikaskumar M

RegisterNumber: 24900247


**RTL realization**

![exp3](https://github.com/user-attachments/assets/76aad4c5-eb40-4451-8691-ec6efa2049fd)


**Timing Diagram**

![Screenshot 2024-10-22 113210](https://github.com/user-attachments/assets/d45afeef-d4b0-4134-b127-d6f5141a5ac7)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

