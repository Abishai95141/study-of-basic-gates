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

 Developed by:ABISHAI KC RegisterNumber: 212223240002
 ***And Gate***
 ![image](https://github.com/Abishai95141/study-of-basic-gates/assets/139335314/20ea9eaa-bd4f-4377-9983-39448af90e87)
 
**Logic symbol & Truthtable**
![image](https://github.com/Abishai95141/study-of-basic-gates/assets/139335314/25a88e3d-2ffd-47ca-bb39-af224af9060e)


**RTL realization Output:** 
![image](https://github.com/Abishai95141/study-of-basic-gates/assets/139335314/44af20d0-8076-4bf0-974c-9623f01091a2)


**RTL**
![image](https://github.com/Abishai95141/study-of-basic-gates/assets/139335314/a1b4406c-c4b6-4c0b-8b7a-b6126a97591a)

***Or Gate***
![image](https://github.com/Abishai95141/study-of-basic-gates/assets/139335314/4ba26ab8-960d-4524-8475-26db2716dc35)

**Logic symbol & Truthtable**
![image](https://github.com/Abishai95141/study-of-basic-gates/assets/139335314/dd560a41-fe18-4ddb-8dfc-dbad35b86183)

**RTL realization Output:** 
![image](https://github.com/Abishai95141/study-of-basic-gates/assets/139335314/cfc2c12d-b798-4f7d-83ab-4af9150ff5da)



**RTL**
![image](https://github.com/Abishai95141/study-of-basic-gates/assets/139335314/9c8c4ca9-9796-4be0-925f-06c6548a63a1)



**Result:**
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.


