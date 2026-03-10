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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: B Prabhanjan
RegisterNumber: 212225040305

```
module de2(a,b,c,d,w,x,y,z,f1,f2);

input a,b,c,d,w,x,y,z;

output f1;

output f2;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

assign f2=((~y & z)|( w & y )|(x & y));

endmodule
```


*/


**RTL realization**

![WhatsApp Image 2026-03-10 at 09 18 46](https://github.com/user-attachments/assets/b698322d-8c89-47f6-94ab-f862f75edee3)

**RTL**

![WhatsApp Image 2026-03-10 at 09 23 03](https://github.com/user-attachments/assets/ee9c98ed-f8cd-4573-87ab-f815e7bf6b64)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

