# Experiment--03-Half-Subtractor-and-Full-subtractor
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
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: NANDHINI.E
RegisterNumber: 22007762 
*/

## Output:

## Truthtable

![halfsubtractor (2)](https://user-images.githubusercontent.com/121998147/214759006-d8bc9361-497b-45a4-94c5-24d3799b76be.png)
![fullsubtractor (2)](https://user-images.githubusercontent.com/121998147/214759026-a0035e13-4517-4259-b06f-53cd8819a7c1.png)


##  RTL realization

![halfsubtractor](https://user-images.githubusercontent.com/121998147/214274696-67b7675c-4b04-4599-8a0b-4ce33ab9e70a.png)
![fullsubtractor](https://user-images.githubusercontent.com/121998147/214274747-ed393e6a-c87b-405a-beb1-848eb6b4750c.png)

## Timing diagram
![half subtractor TD](https://user-images.githubusercontent.com/121998147/214274890-562236bd-5760-4c1e-9c43-e8e75f9f66fc.png) 
![fullsubtractor TD](https://user-images.githubusercontent.com/121998147/214275065-3995a2ef-df6a-42ee-80ba-c8035db54331.png)

## ResulT
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
