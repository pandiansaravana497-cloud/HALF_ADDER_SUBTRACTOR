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

<img width="1531" height="814" alt="Screenshot 2025-11-21 181612" src="https://github.com/user-attachments/assets/fee198a0-038a-4aed-8c9f-2e1ad9ecc095" />


Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 


Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
<img width="936" height="417" alt="Screenshot 2025-11-21 181653" src="https://github.com/user-attachments/assets/e9746d7e-199e-434c-9513-06901bb88577" />
<img width="578" height="281" alt="Screenshot 2025-11-21 184737" src="https://github.com/user-attachments/assets/ec8e2266-e643-45da-a409-cd30ec0dfc34" />





Developed by:B.Pon Saravana Pandian
RegisterNumber:25005762

**RTL Schematic**
<img width="1531" height="814" alt="Screenshot 2025-11-21 181612" src="https://github.com/user-attachments/assets/5c6505c2-ad0f-4bc5-b612-cac97b947501" />
<img width="1528" height="821" alt="Screenshot 2025-11-21 183856" src="https://github.com/user-attachments/assets/28ef5386-9c3b-4c1a-935e-e7e116043ff2" />



**Output/TIMING Waveform**
<img width="1206" height="340" alt="Screenshot 2025-11-21 182942" src="https://github.com/user-attachments/assets/c52acadd-86c1-46e4-9424-d1c8ef285e68" />
<img width="1124" height="328" alt="Screenshot 2025-11-21 185352" src="https://github.com/user-attachments/assets/433909e6-6cb4-4421-8fbd-4d5cf98b905c" />



**Result:**
Thus the a half adder and half subtractor circuit is designed and its truth table is verified in Quartus using Verilog programming .
