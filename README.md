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

Developed by:S Sesha Raghavan RegisterNumber:24900320

**Truthtable**

![image](https://github.com/user-attachments/assets/46f8e3ab-b24c-4636-91ef-46ff3f5d8531)
![image](https://github.com/user-attachments/assets/043a9459-7af4-4146-ba76-ad6e3a0a1114)

**Procedure**

Write the detailed procedure here

**Program:**
![Quartus II 64-Bit - C__altera_13 0sp1_full_adder - full_adder 08-12-2024 12_47_27 PM](https://github.com/user-attachments/assets/ccb842ae-30ad-4b65-8d24-7b498f594714)
![WhatsApp Image 2024-12-08 at 21 46 31_47ee4364](https://github.com/user-attachments/assets/68515db0-98ab-4036-8aa8-219f1a65433c)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**
![RTL Viewer - C__altera_13 0sp1_full_adder - full_adder 08-12-2024 12_48_20 PM](https://github.com/user-attachments/assets/1e98da3f-3a7c-42da-a9d2-3cd84d1e9254)
![WhatsApp Image 2024-12-02 at 14 28 47_085a57db](https://github.com/user-attachments/assets/3d92ed16-d70b-4731-a4ca-e1c6b68d6cce)

**Output Timing Waveform**
![WhatsApp Image 2024-12-02 at 14 28 46_59401a83](https://github.com/user-attachments/assets/137b0adc-2a49-4dcd-90d8-30d68c858f1c)
![WhatsApp Image 2024-12-02 at 14 28 47_a418b562](https://github.com/user-attachments/assets/704168b8-d18a-4a24-8596-51305be1af4f)

**Result:**
![Quartus II 64-Bit - C__altera_13 0sp1_full_adder - full_adder 08-12-2024 12_47_39 PM](https://github.com/user-attachments/assets/0fd4cef1-28e6-471e-8132-390788272a40)
![WhatsApp Image 2024-12-08 at 21 46 32_0a889817](https://github.com/user-attachments/assets/b639290f-6228-49ff-b73e-06c3c954fa8e)

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



