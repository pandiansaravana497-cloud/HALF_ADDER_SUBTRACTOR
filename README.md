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

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
<img width="936" height="417" alt="Screenshot 2025-11-21 181653" src="https://github.com/user-attachments/assets/7807030c-f19f-4e05-a2e3-8c89027bc04c" />
<img width="578" height="281" alt="Screenshot 2025-11-21 184737" src="https://github.com/user-attachments/assets/9cb19dd0-7599-41ef-bffb-760b324b1863" />



/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:B.Pon Saravana Pandian
RegisterNumber:25005762

**RTL Schematic**
<img width="1531" height="814" alt="Screenshot 2025-11-21 181612" src="https://github.com/user-attachments/assets/9f7e5ce1-00b4-4ef2-8988-a0b8c822e15b" />
<img width="1528" height="821" alt="Screenshot 2025-11-21 183856" src="https://github.com/user-attachments/assets/7884c119-14ce-4e47-bc5f-67dad4010863" />


**Output/TIMING Waveform**
<img width="1206" height="340" alt="Screenshot 2025-11-21 182942" src="https://github.com/user-attachments/assets/4c9bdec2-0036-4160-b774-e6c4971fa6fe" />
<img width="1124" height="328" alt="Screenshot 2025-11-21 185352" src="https://github.com/user-attachments/assets/ff5a8037-11b1-4b5b-810d-ccdb058e3357" />


**Result:**
Thus the a half adder and half subtractor circuit is designed and its truth table is verified in Quartus using Verilog programming .
