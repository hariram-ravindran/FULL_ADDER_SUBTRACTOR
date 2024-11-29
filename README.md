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
![WhatsApp Image 2024-11-29 at 18 11 56_5b809f0c](https://github.com/user-attachments/assets/3a93e910-461f-4e76-8565-a18d9014d0a8)

**Procedure**

Write the detailed procedure here 1 Type the program in Quartus software. 2
Compile and run the program. 3 Generate the RTL schematic and save the logic
diagram. 4 Create nodes for inputs and outputs to generate the timing diagram. 5 For
different input combinations generate the timing diagram.


**Program:**
![Screenshot 2024-11-29 174615](https://github.com/user-attachments/assets/9ee22bc1-825a-41ca-b19c-38b9c05d3fa0)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:Hari Ram R
RegisterNumber:24005836
*/

**RTL Schematic**
![Screenshot 2024-11-29 174659](https://github.com/user-attachments/assets/97ab4fe5-d382-4d0c-a461-30ad8b182437)

**Output Timing Waveform**
![Screenshot 2024-11-29 174711](https://github.com/user-attachments/assets/4cfc2e62-4396-41f9-b584-cba1a3419c49)

**Result:**
Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



