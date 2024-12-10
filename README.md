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
![WhatsApp Image 2024-12-10 at 08 02 14_9ee078a0](https://github.com/user-attachments/assets/9a30cad6-c249-476e-88cb-ebfcc5621602)
![WhatsApp Image 2024-12-10 at 08 02 15_8532843c](https://github.com/user-attachments/assets/c6c5fd5d-6e72-4580-b881-b22a8b7eee3e)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: RegisterNumber:*/

**RTL Schematic**
![WhatsApp Image 2024-12-08 at 14 33 16_6e306b46](https://github.com/user-attachments/assets/7742db69-7945-462e-8240-cea9c8fce933)
![WhatsApp Image 2024-12-08 at 14 33 17_638633b2](https://github.com/user-attachments/assets/bc768559-1177-4fc3-a867-5999853a8d56)


**Output/TIMING Waveform**
![WhatsApp Image 2024-12-08 at 14 33 17_ca10a6e2](https://github.com/user-attachments/assets/abbb8025-bf6d-4a2e-8d93-ea9ce01bb08f)
![WhatsApp Image 2024-12-08 at 14 33 17_1df4cbb9](https://github.com/user-attachments/assets/4794b974-afc0-42ac-887c-254296e4d06e)


**Result:**
hence the programm for half adder and half subtractor nd verification of its truth table in quartus using verilog programming is verified
