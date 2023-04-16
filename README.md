Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit
Implementation-of-Half-Adder-and-Full-Adder-circuit
<br> **AIM:**
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**<br>
Hardware – PCs, Cyclone II , USB flasher Software – Quartus prime Theory Adders are digital circuits that carry out addition of numbers.

**Half Adder**<br>
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

**Full Adder**<br>
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin



Figure -01 HALF ADDER
image
![](https://github.com/yuvasri2005/subtractor/blob/51d2d9fe8db940cba556315b8c3bf1b9b4f3ebc1/Images/IMG_20230416_125941.jpg
) 
Figure -02 FULL ADDER
![](
**Procedure**
Connect the supply (+5V) to the circuit Switch ON the main switch If the output is 1, then the led glows.

Program: /* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/ Logic symbol & Truthtable RTL realization

Output:<br>
RTL<br>
TIMING DIAGRAM<br>
TRUTH TABLE<br>
Result:<br>
