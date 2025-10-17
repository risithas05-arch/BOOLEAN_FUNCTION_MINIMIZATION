# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/


**RTL realization**
![499704128-f48cf46e-c6cd-473c-a062-5b4941d7b725](https://github.com/user-attachments/assets/32d1b24f-10da-4731-b6ed-e72447e3ad70)

![499704129-3d0484e9-c0be-4fee-9250-85054a63ffb9](https://github.com/user-attachments/assets/392c7318-c8dd-462c-a8c0-5beb1d325abe)

**Output:**

**RTL**
![499704610-69a16ab8-f043-4400-bd98-2537572ed0d9](https://github.com/user-attachments/assets/b9b8c2d5-3d09-4e70-adbe-b91dc1faca11)
![499704859-17c08537-8853-4dce-839b-456d203df5fa](https://github.com/user-attachments/assets/189f94cf-553b-428e-9ba1-6b9d9c4f5c49)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

