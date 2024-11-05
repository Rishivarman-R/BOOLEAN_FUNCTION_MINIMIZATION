# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WhatsApp Image 2024-10-29 at 10 50 38_d9ee4ebf](https://github.com/user-attachments/assets/dffea22e-2241-4906-8e42-ee5ed7a87b75)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module ex2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24900419

**RTL**
![WhatsApp Image 2024-11-05 at 10 10 36_3423371b](https://github.com/user-attachments/assets/80d0e11c-45a0-4e7a-bdae-94325b40546b)

**Timing Diagram**

![WhatsApp Image 2024-11-05 at 11 05 19_a586d140](https://github.com/user-attachments/assets/474e0741-8d75-4250-8b59-90dbac1bb69f)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

