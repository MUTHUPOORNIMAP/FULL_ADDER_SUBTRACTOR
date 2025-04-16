# FULL_ADDER_SUBTRACTOR
# Name: Muthu Poornima P
# Reg no: 212224240099

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![image](https://github.com/user-attachments/assets/5ddb81a2-0467-422c-a2c4-fd37140d0af6)
![image](https://github.com/user-attachments/assets/6e7bdc7f-c5da-4a0b-b9fb-6b705c3d7e36)




**Procedure**

**1.Type the program in Quartus software.**

**2.Compile and run the program.**

**3.Generate the RTL schematic and save the logic diagram.**

**4.Create nodes for inputs and outputs to generate the timing diagram.**

**5.For different input combinations generate the timing diagram.**

**Program:**

![image](https://github.com/user-attachments/assets/010c3b36-f1b3-4c2a-adcd-bb3cb4dcc5ea)
![image](https://github.com/user-attachments/assets/7658e73f-222d-437b-b895-4a9ad325952d)




**RTL Schematic**

![image](https://github.com/user-attachments/assets/ebc63514-3c6c-4602-afe1-17d078ae0fa5)
![image](https://github.com/user-attachments/assets/2e1f2e35-7949-4033-86a1-797929a22472)



**Output Timing Waveform**

![image](https://github.com/user-attachments/assets/dc6ffd40-ed9d-4427-a72f-a98b9465ec0a)
![image](https://github.com/user-attachments/assets/eed48526-2d41-4e09-bcb7-274ae6d43f4a)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



