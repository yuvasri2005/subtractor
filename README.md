Experiment--03-Half-Subtractor-and-Full-subtractor
Implementation-of-Half-subtractor-and-Full-subtractor-circuit

<br> **AIM:**
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.


**Equipments Required:**<br>
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime


**Half subtractor**<br>

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.

Sum = X'Y+XY' = X ⊕ Y Carry=X'Y

**Full subtractor**<br>

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow

Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin



Figure -01 HALF SUBTRACTOR
image
![](https://github.com/yuvasri2005/subtractor/blob/51d2d9fe8db940cba556315b8c3bf1b9b4f3ebc1/Images/IMG_20230416_125941.jpg
) 
Figure -02 FULL SUBTRACTOR
![](https://github.com/yuvasri2005/subtractor/blob/376244a8834bd649440d26fae4c8ddc1a37aff5d/Images/IMG_20230416_125957.jpg) 
**Procedure**
Connect the supply (+5V) to the circuit Switch ON the main switch If the output is 1, then the led glows.

**Program:** /* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/ Logic symbol & Truthtable RTL realization*/
![](https://github.com/yuvasri2005/subtractor/blob/0b7dd4712ae66381488762aab68e1b2de05c5b4d/Images/IMG_20230416_125920.jpg) 
**Output:**<br>
RTL<br>
TIMING DIAGRAM<br>
 **FULL SUBTRACTOR** <br>![](https://github.com/yuvasri2005/subtractor/blob/0b7dd4712ae66381488762aab68e1b2de05c5b4d/Images/IMG_20230416_130122.jpg)
**HALF SUBTRACTOR**
![](https://github.com/yuvasri2005/subtractor/blob/0b7dd4712ae66381488762aab68e1b2de05c5b4d/Images/IMG_20230416_130049.jpg) 
**TRUTH TABLE**<br>
![](https://github.com/yuvasri2005/subtractor/blob/0b7dd4712ae66381488762aab68e1b2de05c5b4d/Images/IMG_20230416_130155.jpg) 
**Result:**<br>
 Thus the half subtractor and full subtractor circuits are designed and the truth tables is
verified using quartus software.
