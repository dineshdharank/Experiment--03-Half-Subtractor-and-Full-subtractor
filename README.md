## Name: Dineshdharan.K
## Reg: 23014095

## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:

Half Subractor:

![Screenshot 2023-12-15 220633](https://github.com/dineshdharank/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980096/93e2f681-fff4-423c-b007-f4748e546aa8)

Full Subractor:

![Screenshot 2023-12-15 220026](https://github.com/dineshdharank/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980096/ef13056d-5245-4835-a929-27b30ac96649)


## Truthtable:

Half Subractor:

![Screenshot 2023-12-15 213240](https://github.com/dineshdharank/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980096/bd239acf-fa79-4073-aa77-e089a9d98a60)

Full Subractor:

![Screenshot 2023-12-15 213300](https://github.com/dineshdharank/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980096/ffb0dd52-cd48-4c8c-b2c3-552987cadbc9)


##  RTL realization

Half Subractor:

![Screenshot 2023-12-15 215014](https://github.com/dineshdharank/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980096/bc4c3a0e-b31f-43a2-aa08-ca1873b1e56d)

Full Subractor:

![Screenshot 2023-12-15 184123](https://github.com/dineshdharank/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980096/9470c803-3f52-4ff3-9b9b-add9ad2287bb)


## Timing diagram

Half Subractor:

![Screenshot 2023-12-15 213343](https://github.com/dineshdharank/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980096/701afdd9-d349-4352-9ad1-b07a8fa87357)

Full Subractor:

![Screenshot 2023-12-15 213410](https://github.com/dineshdharank/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145980096/b3881f57-5592-4d5c-a7fc-d878eca9e796)



## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
