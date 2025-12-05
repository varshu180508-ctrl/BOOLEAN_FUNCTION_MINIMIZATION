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


/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 


Developed by:Dhanvarsini.S
RegisterNumber:2501284


**RTL realization**
<img width="1920" height="1200" alt="Screenshot (86)" src="https://github.com/user-attachments/assets/df0fb9c6-9af4-4f5f-82c7-046ca143a0b8" />
<img width="1920" height="1200" alt="Screenshot (89)" src="https://github.com/user-attachments/assets/c2b8af20-b6f7-479d-b409-e2f01a5f7bce" />




**RTL**
<img width="1920" height="1200" alt="Screenshot (87)" src="https://github.com/user-attachments/assets/4690cbb9-f1f3-4d79-bd02-5e2f686b0845" />
<img width="1920" height="1200" alt="Screenshot (90)" src="https://github.com/user-attachments/assets/b7935607-be88-46b8-be93-d2c8b397feb5" />




**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

