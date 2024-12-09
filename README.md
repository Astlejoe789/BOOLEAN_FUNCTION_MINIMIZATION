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

```
Developed by:ASTLE JOE A S
RegisterNumber:24004571
(i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
(ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```


**RTL realization**
![WhatsApp Image 2024-12-09 at 09 36 02_177e1729](https://github.com/user-attachments/assets/cf12ddd8-e3cd-4d7e-9a88-a4960c219ea0)
![WhatsApp Image 2024-12-09 at 09 36 03_28dfa742](https://github.com/user-attachments/assets/72549e90-4778-431c-a475-d842300db712)

**Waveform**
![WhatsApp Image 2024-12-09 at 09 36 04_18ed9824](https://github.com/user-attachments/assets/637cc87d-4d0f-48bb-b8e5-8b2beb403e3e)
![WhatsApp Image 2024-12-09 at 09 36 04_ff9d398b](https://github.com/user-attachments/assets/dd30e804-7ccf-4441-8cbb-9acf925510b3)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

