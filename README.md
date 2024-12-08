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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

```
1)
module digital2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```
```
2)
module digital22(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```
Developed by: M.Chandru

RegisterNumber: 24900224

**Output:**

<img width="500" alt="image" src="https://github.com/user-attachments/assets/b1c20454-4cab-4d3e-bbbc-a537e794956b">

<img width="595" alt="image" src="https://github.com/user-attachments/assets/7e2788f4-262b-41c4-8632-8dc2f6922d4b">



**Timing Diagram**

<img width="752" alt="image" src="https://github.com/user-attachments/assets/0e63e979-e83a-4ca3-a4ae-bb30d4853db0">


<img width="751" alt="image" src="https://github.com/user-attachments/assets/4906c0cd-a954-46fb-a641-e78687e06487">

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

