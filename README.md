# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by:lingeswaran k
RegisterNumber:22005148
*/
Logic symbol & Truthtable
![image](https://user-images.githubusercontent.com/119103865/213090700-466c3b77-e71f-430b-a534-6c85a8e7715f.png)

RTL realization

### Output:
### RTL
half adder
![image](https://user-images.githubusercontent.com/119103865/213090787-b126c567-f9ec-4b4e-8933-44cac622c3e8.png)

full adder
![image](https://user-images.githubusercontent.com/119103865/213090828-f82427fd-a956-4c27-bc1e-b1984f30c433.png)

### TIMING DIAGRAM
half adder
![image](https://user-images.githubusercontent.com/119103865/213090924-b667bb0f-6126-426c-9509-526c44119917.png)
full adder
![image](https://user-images.githubusercontent.com/119103865/213090985-c2afdfcf-c3fe-4b76-8d55-eba69f5ccab3.png)

### TRUTH TABLE 
half adder
![image](https://user-images.githubusercontent.com/119103865/213091047-df66f658-f164-438b-9a2b-fa7370e91385.png)
full adder
![image](https://user-images.githubusercontent.com/119103865/213091091-be01e733-0d78-49c3-9ec3-ce34872e6a32.png)

### Result:
Thus the different digital IC's are studied and the truth table for differnt logic gates are verified.
