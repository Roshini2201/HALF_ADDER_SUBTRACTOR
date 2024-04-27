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

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.
 **Developed by: ROSHINI S**
 **RegisterNumber: 212223240142**

**HALF ADDER**

**Program:**

![ex 3 p](https://github.com/Roshini2201/HALF_ADDER_SUBTRACTOR/assets/154105318/1ef3e871-673d-4094-9999-15b6503ca214)



**RTL Schematic**

![Screenshot 2024-04-27 102146](https://github.com/Roshini2201/HALF_ADDER_SUBTRACTOR/assets/154105318/e3948dcb-9ab4-4d8c-b480-b905e0a073cc)

**Truthtable**

![Screenshot 2024-04-27 102342](https://github.com/Roshini2201/HALF_ADDER_SUBTRACTOR/assets/154105318/7002b948-c581-465a-9d25-442f74565d33)

**Output/TIMING Waveform**

![Screenshot 2024-04-27 103339](https://github.com/Roshini2201/HALF_ADDER_SUBTRACTOR/assets/154105318/e83395d2-67ee-4466-91fa-b12f26f782b6)


**HALF SUBTRACTOR**

**Program:**

![Screenshot 2024-04-27 102525](https://github.com/Roshini2201/HALF_ADDER_SUBTRACTOR/assets/154105318/c2e607de-e4d1-4a60-9994-b421421c7797)

**RTL Schematic**

![Screenshot 2024-04-27 102600](https://github.com/Roshini2201/HALF_ADDER_SUBTRACTOR/assets/154105318/7c59597e-2458-41f1-9490-a1c65a7a4396)

**Truthtable**

![Screenshot 2024-04-27 102720](https://github.com/Roshini2201/HALF_ADDER_SUBTRACTOR/assets/154105318/4591cd1f-a8b5-4821-b3de-b10a972c8889)

**Output/TIMING Waveform**

![image](https://github.com/Roshini2201/HALF_ADDER_SUBTRACTOR/assets/154105318/76dc2c7f-d0dc-48a4-a13f-39b17852088d)

**Result:**
Thus the program was successfully verified.
