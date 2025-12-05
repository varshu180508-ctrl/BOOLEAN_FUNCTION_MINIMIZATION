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
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule


module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

Developed by:Dhanvarsini.S
RegisterNumber:25012184


**RTL realization**
<img width="1920" height="1200" alt="Screenshot (86)" src="https://github.com/user-attachments/assets/d1079a87-442f-4f90-84e2-afe5e1fbc626" />
<img width="1920" height="1200" alt="Screenshot (89)" src="https://github.com/user-attachments/assets/c59703cd-d099-473d-b99a-675ab6860b60" />

**RTL**
<img width="1920" height="1200" alt="Screenshot (87)" src="https://github.com/user-attachments/assets/8d771975-4f21-40e6-84ad-d3ad2809fd82" />
<img width="1920" height="1200" alt="Screenshot (90)" src="https://github.com/user-attachments/assets/ee4d7877-2b7d-49ae-ab7a-9069c669a466" />



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

