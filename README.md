# BOOLEAN_FUNCTION_MINIMIZATION
**Date:05/12/2025**

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
Boolean Function
------------------------------------------------
F(A,B,C,D)=AB+CD+AD
```

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule

```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by:Mathiyazhagan RegisterNumber:25018155*/

**Output:**
<img width="932" height="547" alt="diagram 2 ex" src="https://github.com/user-attachments/assets/36d4fcba-4a92-4dfb-9f06-6da4b470b976" />


**RTL realization**
**RTL**
![ex2 output](https://github.com/user-attachments/assets/b3a37f44-6963-45ad-9698-3ae4bf803f56)

**Timing Diagram**

**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
.
.
.

.

.
.

.
.

.
.
.

.
.
.

.
.
.

.
.

.
.

.
.
.

.
..

.
.


.
.
.
.

.
.
.
.
.
.
.
.
.
.

.

.


.
.
.
.
.
.
.

.



.
.
.
.

.

.
.
.


.

.

.

.

.
.
.
.

.
.
.

.
.
.
.
.
.
.

.
.
.
\.

.
.
.
.
.

.
.
.
.

.
.
.

.
.
.
.

.
.
.
.
.
.
.
.
.
.

.
.
.




.
.
.
.
.

.
.

.

.
.

.
.
.

.
.
.
.
.

.
.
.
.
.

..


.
.
.
.

.
.



