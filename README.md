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

Developed by:Ajay.J

RegisterNumber:24004969

```
module experiment2(A,B,C,D,f1,w,x,y,z,f2);
input A,B,C,D,w,x,y,z;
output f1,f2;
assign f1=((~B&~D)|(~A&B&D)|(A&B&~C));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

**RTL realization**

![image](https://github.com/user-attachments/assets/4a6ce00d-5d0c-487d-ba13-907ffcc2613d)

**Truth Table**

![image](https://github.com/user-attachments/assets/85c1ced5-57dd-4e02-8a35-5b66f60678ff)

![image](https://github.com/user-attachments/assets/ee5f5bea-01ca-4a4c-9293-69501cc17edd)


**Output:**

**RTL**

![image](https://github.com/user-attachments/assets/93240d3b-5265-4be7-a19d-8eac231484e5)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

