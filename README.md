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

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
Developed by: SESHAN J RegisterNumber: 24003142*/

module expé(sun, cout, a,b,cin);       
output sun     
output cout,      
Input a,      
Input bi     
Input cin,       
wire si,c1.c2,       
sor(si,a,b);        
and(cl,a,b);     
xor(sum, si, cin);        
and(c2,51,cin);         
or (cout, c2, 1);       
endmodule       


module expla(df,bo,a,b,bin);         
output of;         
output bo,       
Input a       
Input B     
Input bin;    
wire w,w,w    
assign winab    
assign w2-(-as);     
assign w3+(-wbin);    
assign ofwibing      
assign, ho-w2/wa       
endmodule      
**RTL Schematic FULL-ADDER**
![image](https://github.com/user-attachments/assets/966a2500-d38c-42ca-be97-4f0112a1a899)
**FULL-SUBTRACTOR**
![image](https://github.com/user-attachments/assets/b11fba00-3795-4f3d-93f4-edca80efd1a7)

**Output Timing Waveform Full-Adder**
![image](https://github.com/user-attachments/assets/cc1c5c1d-5ab4-4f2a-a066-efbf547b8562)
**FULL-SUBTRACTOR**
![image](https://github.com/user-attachments/assets/4d612dce-4034-437e-8081-7afde9351c6b)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



