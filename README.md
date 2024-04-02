### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

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


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by: AMEESHA JEFFI J RegisterNumber: 212223220007

 ## PROGRAM
 
 ![312929661-f60ca1fc-49be-4e9f-8527-2ff7aea91732](https://github.com/ameeshajeffi/study-of-basic-gates/assets/150773598/e155c2a4-28dd-4577-abb0-6ab021ca2c62)

## Logic symbol & Truthtable

![312929686-afd50340-e68f-4779-a59a-fdd4cf927bee](https://github.com/ameeshajeffi/study-of-basic-gates/assets/150773598/f47b41fb-1387-4047-b721-7668b8e6113b)

## RTL realization

![312929719-240dcbc2-04ff-4fa1-a7ac-702c75144584](https://github.com/ameeshajeffi/study-of-basic-gates/assets/150773598/023ff780-96f9-42e3-8e33-cfb2d20ec4ed)

## OUTPUT

![312929813-8c2a01fa-7cfb-4411-a938-efbce0f96ba3](https://github.com/ameeshajeffi/study-of-basic-gates/assets/150773598/ecd8a4d1-04df-45eb-9370-de2f55c5be52)

## Result:

Thus the different digital IC’s are studied and the truth table for different logic gates are verified.
