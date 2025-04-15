**Name: Niranjan V**

**REGISTER NO: 212224110042**

### EX NO: 2 - BOOLEAN FUNCTION IMPLEMENTATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus**

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

![Screenshot 2025-03-20 110540](https://github.com/user-attachments/assets/76d94040-d131-4bcd-b178-d95b6dc5c189)


**Truth Table**

![Web_Photo_Editor](https://github.com/user-attachments/assets/f2184889-a0c0-45e0-9e93-dc69780e7622)

![Web_Photo_Editor (1)](https://github.com/user-attachments/assets/c289b56b-3b37-4774-8366-5ebc01a25a2d)


**Logic Diagram**

![f1 jpeg](https://github.com/user-attachments/assets/045a9076-ba86-48d2-864f-31640527fc72)

![f2 jpeg](https://github.com/user-attachments/assets/8ec98cd4-48b9-4e8e-9d94-150d643213c4)


**RTL realization**

![Screenshot 2025-03-20 110610](https://github.com/user-attachments/assets/256901cd-0a9c-4181-918e-6600f94bcf49)


**WAVEFORM**

![Screenshot 2025-04-10 112252](https://github.com/user-attachments/assets/d49e5e97-9655-471f-b06b-c11ad2cd6ba7)


**Result:**

Thus the given logic functions are implemented and their operations are verified using Verilog programming.
