Aim:-
To implement and verify logical shift, arithmetic shift, rotate, and rotate with carry operations (RS, LS, ARS, ALS, RR, RL, RRC, RLC) using an 8-bit shift register in Logisim.


Theory:-
A shift register is a sequential digital circuit made using flip-flops that is used to store and shift binary data. In an 8-bit shift register, 8 flip-flops are connected such that each flip-flop stores one bit, and data is transferred from one stage to another on each clock pulse.

Shifting operations are essential in digital systems for data manipulation, arithmetic operations, and communication systems.

Logical Right Shift (RS):
All bits are shifted one position to the right and the most significant bit (MSB) is filled with 0.

Logical Left Shift (LS):
All bits are shifted to the left and the least significant bit (LSB) is filled with 0.

Arithmetic Right Shift (ARS):
Similar to logical right shift, but the MSB (sign bit) is preserved and copied during shifting.

Arithmetic Left Shift (ALS):
Same as logical left shift; bits shift left and LSB is filled with 0.

Rotate Right (RR):
Bits are shifted to the right in a circular manner and the LSB is moved to the MSB.

Rotate Left (RL):
Bits are shifted to the left circularly and the MSB is moved to the LSB.

Rotate Right with Carry (RRC):
The LSB is moved to the carry and the previous carry is inserted into the MSB.

Rotate Left with Carry (RLC):
The MSB is moved to the carry and the previous carry is inserted into the LSB.


Procedure:-
1. Open Logisim and create a new circuit.
2. Place 8 D flip-flops and arrange them in a row to form an 8-bit shift register.
3. Label the outputs as Q7, Q6, Q5, Q4, Q3, Q2, Q1, and Q0.
4. Connect a common clock signal to all flip-flops.
5. Set the enable input of all flip-flops to logic HIGH (1).
6. Provide initial input values manually.
7. Make connections based on the required operation:
    * For logical right shift, shift bits right and insert 0 at MSB.
    * For logical left shift, shift bits left and insert 0 at LSB.
    * For arithmetic right shift, shift right and copy MSB.
    * For arithmetic left shift, shift left similar to logical left shift.
    * For rotate right, connect LSB to MSB.
    * For rotate left, connect MSB to LSB.
    * For rotate right with carry, move LSB to carry and carry to MSB.
    * For rotate left with carry, move MSB to carry and carry to LSB.
8. Apply clock pulses using the clock component.
9. Observe and record outputs after each clock pulse.


Observation:-
The outputs of the 8-bit shift register were observed for different operations after applying clock pulses.

* Bits shifted correctly in both left and right directions.
* Rotation operations showed circular movement of bits.
* Arithmetic right shift preserved the sign bit.
* The observed outputs matched the expected behavior for all operations.


Result:-
The shift register operations including logical shift, arithmetic shift, rotate, and rotate with carry were successfully implemented and verified in Logisim.

Conclusion:-
The experiment was successfully performed using an 8-bit shift register. All operations behaved as expected according to theoretical concepts. This experiment helped in understanding data shifting, rotation mechanisms, and the importance of clock signals in sequential circuits.