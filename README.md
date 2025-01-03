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
Half Adder Truth Table

![Screenshot 2024-12-31 052548](https://github.com/user-attachments/assets/be6c54f1-3dd9-4b92-92bd-b0b8189c5321)

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor
 Half Subtractor Truth Table
 
 ![Screenshot 2024-12-31 052920](https://github.com/user-attachments/assets/efaf54b1-0ab5-460a-8014-651f7d09ce2e)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: RegisterNumber:*/24900725

 Half Adder

  ![Screenshot 2025-01-02 165800](https://github.com/user-attachments/assets/849ebb48-c88c-4a15-9ff4-b66bc3b9d50c)


 Half Subtractor

 ![Screenshot 2025-01-02 165812](https://github.com/user-attachments/assets/b5555304-b2df-407d-bcac-8ab3e56b8902)

 
**RTL Schematic**
Half adder

![Screenshot 2024-12-31 053352](https://github.com/user-attachments/assets/3af032cc-e081-47d6-9020-4bc4a6eb1ebf)

Half Subtractor

![Screenshot 2024-12-31 053449](https://github.com/user-attachments/assets/91ec4d58-a80c-4f81-b41b-771d831b4794)

**Output**

Half Adder

![Screenshot 2024-12-31 053549](https://github.com/user-attachments/assets/2b3d3193-bf3b-42cd-9654-af83860cfdd2)

Half Subtractor

![Screenshot 2024-12-31 053655](https://github.com/user-attachments/assets/8922bd1e-465b-419f-b8df-fd476d50fdfd)

**Result:**
hence the programm for half adder and half subtractor nd verification of its truth table in quartus using verilog programming is verified
