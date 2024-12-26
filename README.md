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

/* 1.Type the Verilog program in Quartus Prime to implement the 4-bit Serial-In Serial Out (SISO) Shift Register. 2.Compile and run the program to ensure the design is error-free. 3.Generate the RTL schematic to visualize the cascading D flip-flop connections and save it for documentation. 4.Create nodes for the serial input (SI), clock (CLK), and serial output (SO) to observe the shifting process during simulation. 5.Simulate the design for different input serial data patterns and observe the timing diagrams. */

**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by:Akshaay Vardhan RegisterNumber:240073833
*/

![WhatsApp Image 2024-12-26 at 10 13 25_a2dab289](https://github.com/user-attachments/assets/d41cb913-c907-421b-9f23-3519709b83a8)


**RTL LOGIC FOR 4 Bit Ripple Counter**

![WhatsApp Image 2024-12-26 at 10 13 25_d3488f17](https://github.com/user-attachments/assets/aff98d11-b49b-4271-b9ff-5b18d135c464)

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![WhatsApp Image 2024-12-26 at 10 13 24_db7775b0](https://github.com/user-attachments/assets/5e36c4d9-5e97-49a5-836a-8ca3ef3d5944)

**RESULTS**

Thus, the 4-bit Ripple Counter was successfully implemented, and its functionality was validated using the truth table.

