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

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
```
Developed by: ADITAAYAN M
RegisterNumber:21222304006
```

**Full Adder:**
![316394096-a297a7e6-cf3f-44dc-b3a6-26e15d2eac4e](https://github.com/Aditaayan/FULL_ADDER_SUBTRACTOR/assets/147473394/b1635526-c14d-4639-9b8c-39d93eeb9516)




**Full Subtractor**


![316394149-5c08e4b6-2ccb-4e62-91a2-384b29e10520](https://github.com/Aditaayan/FULL_ADDER_SUBTRACTOR/assets/147473394/e01b6e8a-4d37-43fe-a7d1-938f5945aa37)


**RTL Schematic**

**Full Adder:**

![316394691-5f9c5c4e-14f9-47ad-aa97-825298eb9f4c](https://github.com/Aditaayan/FULL_ADDER_SUBTRACTOR/assets/147473394/ded4055d-9f6a-424b-9922-78a85e729181)

**Full Subtractor**

![316394721-f5c1c7b6-c5ea-451a-b946-6b0c4b0c3b3c](https://github.com/Aditaayan/FULL_ADDER_SUBTRACTOR/assets/147473394/9980ec17-7b56-4433-82c8-13e718396d29)

**Output Timing Waveform**

**Full Adder:**

![316394758-44b12040-5bc1-41c7-ad1c-aec71a2ea415](https://github.com/Aditaayan/FULL_ADDER_SUBTRACTOR/assets/147473394/c95bf5ef-2431-40ba-9994-e043bdb08fe4)


**Full Subtractor**

![316394779-668079eb-68f5-49af-8c09-23fbbcc8d30e](https://github.com/Aditaayan/FULL_ADDER_SUBTRACTOR/assets/147473394/4c3491f8-2917-4c99-8ce2-3e8232e91014)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.
