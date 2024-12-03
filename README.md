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
Developed by:Hiba Nasreen M
RegisterNumber:24900188
```
```
module booleanfn(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule
```
**RTL realization**
![Screenshot 2024-12-02 232011](https://github.com/user-attachments/assets/66834aa3-138e-411e-98be-8e249cf3f668)

**Output:**
![Screenshot 2024-12-03 070755](https://github.com/user-attachments/assets/b8e7d954-136c-456f-8da4-3dcfa43a6d07)



**Timing Diagram**
![Screenshot 2024-12-03 081920](https://github.com/user-attachments/assets/ed5146d2-2cfb-4969-ac7b-57de706869be)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

