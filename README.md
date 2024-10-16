### Study-of-basic-gates

*AIM:* 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

*Equipments Required:*

Software – Quartus prime 

*Theory*

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

*AND gate*

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

*OR gate* 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

*NOT gate*

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

*NAND gate*

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

*NOR gate*

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

*Ex-OR gate*

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

*Ex-NOR gate*

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

*Procedure* 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


*PROGRAM*

Program for logic gates and verify its truth table in quartus using Verilog programming

<br>
<br>
module exp1(a,b,c,d,e,x,y,z);<br>
input a,b;<br>
output c,d,e,x,y,z;<br>
and(c,a,b);<br>
or(d,a,b);<br>
xor(e,a,b);<br>
nand(x,a,b);<br>
nor(y,a,b);<br>
xnor(z,a,b);<br>
endmodule<br>
<br>
<br>

Developed by:MURALI S <br>
RegisterNumber: 212222230088

 
*Logic symbol & Truthtable*
![WhatsApp Image 2024-03-14 at 21 49 55_76ff7873](https://github.com/VineelaShaik/study-of-basic-gates/assets/144340862/e65b5e58-22c9-4c20-95b0-c729106d396f)
![WhatsApp Image 2024-03-14 at 21 49 55_f72b0c92](https://github.com/VineelaShaik/study-of-basic-gates/assets/144340862/2b11f4d9-a8cb-45c0-bb83-9617800d3311)

*RTL realization Output:* 
![Screenshot 2024-03-14 212501](https://github.com/VineelaShaik/study-of-basic-gates/assets/144340862/5b9261a9-3c06-4a8f-aee4-ca5de0b351bd)

*RTL*
![Screenshot 2024-03-14 212101](https://github.com/VineelaShaik/study-of-basic-gates/assets/144340862/1c4ece56-94ae-4840-b241-61dd4a06bbe6)

*Result:*
Thus the different digital IC's are studied and the truth table for different logic gates are verifie
