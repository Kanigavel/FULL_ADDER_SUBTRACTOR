# FULL_ADDER_SUBTRACTOR

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

**Procedure**

Write the detailed procedure here

**Program:**
![Screenshot 2025-04-23 185501](https://github.com/user-attachments/assets/00dcef6d-0330-4fef-bfb9-4e8355827f94)
![Screenshot 2025-04-23 185428](https://github.com/user-attachments/assets/175fc469-be0c-4b3d-9da2-09315390d60c)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:212224240070

*/

**RTL Schematic**
![Screenshot 2025-04-23 184814](https://github.com/user-attachments/assets/5950ddda-6b7e-45a9-a7f1-a9088d730a75)

![Screenshot 2025-04-23 185230](https://github.com/user-attachments/assets/d14ca943-9af0-43ca-95e0-2128d3db1181)

**Output Timing Waveform**
![Screenshot 2025-04-23 184942](https://github.com/user-attachments/assets/0c7deba6-f185-403e-9628-b5de52b5a4d8)
![Screenshot 2025-04-23 185335](https://github.com/user-attachments/assets/6666eadf-6050-4241-bceb-7d25960f85a2)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



