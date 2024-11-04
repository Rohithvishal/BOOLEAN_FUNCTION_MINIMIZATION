# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**
![WhatsApp Image 2024-10-14 at 14 06 02_a1d2aee4](https://github.com/user-attachments/assets/47d9fb25-6d79-4ef3-abe3-5dfe408d09a1)

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
module exp2-1(a,b,c,d,f1);
input a,b,cd;
output f1;
assign f1=((~B&~D)|(~A&B&D)|(A&B&~C));
endmodule
module exp2-2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/24000942


**RTL realization**
![WhatsApp Image 2024-11-04 at 14 25 26_d3dc440f](https://github.com/user-attachments/assets/b514e204-13f4-4a08-b015-25f25d8b3186)
![WhatsApp Image 2024-11-04 at 14 25 27_aa4aec56](https://github.com/user-attachments/assets/a41e4712-20fb-4e0a-a034-8844242d5aa6)


**Timing Diagram**
![WhatsApp Image 2024-11-04 at 14 25 27_8f0fc5e3](https://github.com/user-attachments/assets/c1aa5acd-26be-4de3-ae3f-2973b2aef55a)
![WhatsApp Image 2024-11-04 at 14 25 27_55bba3c2](https://github.com/user-attachments/assets/8c516c45-9f44-4de3-bcfc-cd36a5eafe57)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

