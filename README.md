**EX-1**                                                                  IMPLEMENTATION OF BASIC LOGIC GATES   
**DATE:**

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

**NAME : SUBASH E**  
**REGISTER NUMBER : 212223040209**

## AND GATE

**PROGRAM**

![Screenshot 2024-04-10 133440](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/ea8256d6-9793-43aa-9599-8edb471afa27)

 
**Logic symbol & Truthtable**

![Screenshot 2024-04-04 111518](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/e333ab21-f7bf-4aa0-8a6b-f69c57451122)


**RTL**

![EX-1 And gates](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/e6d8cd84-a6f9-494a-8dbe-14f5232a24b1)


**RTL realization Output:** 

![EX-1 AND](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/ff9b3046-63ed-449d-bba6-e1a0cff0279b)

## OR GATE

**PROGRAM**

![image](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/ddeb460c-e5f3-45b6-a115-169e4397563c)


**Logic symbol & Truthtable**

![Screenshot 2024-04-04 111542](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/7c6f142b-46a3-4e36-a4c7-76008d1b9832)


**RTL**

![Screenshot 2024-04-03 203536](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/18e815c2-415d-48a5-881e-a4073c55509d)


**RTL realization Output:** 

![Screenshot 2024-04-03 203127](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/e4c2528d-b615-49a1-8c0d-eae421b8adcc)

## NOT GATE

**PROGRAM**

![image](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/1cad371c-4463-4d9d-a033-bdad05e1b6d1)


**Logic symbol & Truthtable**

![image](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/19d8cb59-7eab-4f7b-a45d-296947b83146)


**RTL** 

![Screenshot 2024-04-03 210519](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/b113887a-9711-4cc6-a370-65011076d102)


**RTL realization Output:**

![Screenshot 2024-04-03 210033](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/91e6f5d3-07b5-4f9e-8304-e633aa560a0a)


## NAND GATE

**PROGRAM**

![image](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/d24d2a06-0780-4e5d-8f4f-5cd5825b96a0)


**Logic symbol & Truthtable**

![Screenshot 2024-04-04 111602](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/a0137613-8911-48f3-b17b-8f2829320975)


**RTL**

![image](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/4af553bd-b913-4db8-a3ec-089a9482ad06)


**RTL realization Output:**

![Screenshot 2024-04-03 211416](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/cd6af132-c459-4b8d-ae94-7acece134f68)


## NOR GATE

**PROGRAM**

![image](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/bbc077de-ee0e-446b-a62e-7117b5221b51)


**Logic symbol & Truthtable**

![Screenshot 2024-04-04 111611](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/eb93295d-0d69-4b8f-bedd-99ec4f99c4aa)


**RTL**

![Screenshot 2024-04-03 212002](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/7cfffafe-e298-41f7-9563-46a1f94f5972)


**RTL realization Output:**

![Screenshot 2024-04-03 211930](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/cdfb5e64-a652-4bf0-89d8-1d07528a4a42)


## EX-OR GATE 

**PROGRAM**

![image](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/d286b753-55ac-4244-a3bd-9b43f11fab22)


**Logic symbol & Truthtable**

![Screenshot 2024-04-04 111554](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/dfcd8129-dc9c-47bf-9dc1-8d34142f0f81)


**RTL** 

![Screenshot 2024-04-03 212819](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/d473eed3-f79f-48cf-a817-df2ec6c0eec2)


**RTL realization Output:**

![Screenshot 2024-04-03 212735](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/dbf2c102-470c-4de1-93f4-68449fe7390e)


## EX-NOR

**PROGRAM**

![image](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/395f90c6-e3da-451d-baa9-93e89af26ad9)

**Logic symbol & Truthtable**

![Screenshot 2024-04-04 111636](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/ed25b34e-8a78-4fd1-9b9b-86894a498f7d)


**RTL**

![Screenshot 2024-04-03 213908](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/0a08d115-8fe8-4943-b322-66f16da0ec08)

**RTL realization Output:** 

![Screenshot 2024-04-03 211930](https://github.com/subha-shinibalasubramanian/study-of-basic-gates/assets/164154478/b87a09f9-a913-4428-bcb4-8a1d92176656)



**Result:**  
Thus,truth table of logic gates in Quartus II using Verilog programming is executed successfully and verified 


