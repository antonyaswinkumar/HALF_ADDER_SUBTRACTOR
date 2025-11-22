# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**
1.Truthtable for HALFADDER:

<img width="1024" height="1024" alt="halfadder" src="https://github.com/user-attachments/assets/a0cced50-a895-45a8-8d5e-d2e451a87858" />


2.Truthtable for HALFSUBTRACTOR:

<img width="1024" height="1024" alt="halfsubtractor " src="https://github.com/user-attachments/assets/a1463a8e-5587-453c-99e4-78617ce90d38" />


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming:

<img width="1920" height="1080" alt="program 3" src="https://github.com/user-attachments/assets/6557c4b7-4384-47fe-b69a-675d7c7f5b0f" />
Developed by: RegisterNumber: 25015904

**RTL Schematic**

<img width="1920" height="1080" alt="rtl 3" src="https://github.com/user-attachments/assets/d40e153d-13ba-4531-a2cc-cb52e7e3389d" />

**Output/TIMING Waveform**

<img width="1920" height="1080" alt="waveform 3" src="https://github.com/user-attachments/assets/e219eb13-2249-468f-9218-6cba6138900b" />

**Result:**
Thus , the experiment to design a half adder and half subtractor circuit and verifying its truth table in Quartus II software using Verilog programming is executed successfully.

