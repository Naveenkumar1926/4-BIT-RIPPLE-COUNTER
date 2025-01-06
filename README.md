# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

/* write all the steps invloved */

**PROGRAM**

Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

Developed by: NAVEEN KUMAR S RegisterNumber: 24900140

![Screenshot 2024-12-25 132548](https://github.com/user-attachments/assets/225eb79e-ed09-4c2c-9e5d-57dd99ef4419)


**RTL LOGIC FOR 4 Bit Ripple Counter**
![Screenshot 2024-12-25 132559](https://github.com/user-attachments/assets/3a170be0-97d1-4217-823f-411797d86600)

 
**TIMING DIGRAMS FOR 4 Bit Ripple Counter**
![Screenshot 2024-12-25 132651](https://github.com/user-attachments/assets/4d0a6834-1fbd-4940-8b20-27b156971f89)


**RESULTS**
Thus the 4 Bit Ripple Counter using verilog and validating their functionality using the fuctionality table is implemented successfully.
