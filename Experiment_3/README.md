Aim:-
To design and simulate a 4-bit Ripple Carry Adder using Logisim software and verify its functionality.

Theory:-
A Ripple Carry Adder (RCA) is a combinational circuit used to perform binary addition of multi-bit numbers. It is constructed by cascading multiple full adders, where the carry output of each stage is passed as the carry input to the next stage.

A Full Adder adds three bits:
Two significant bits (A and B)
One carry input (Cin)

It produces:
Sum (S)
Carry output (Cout)

The logic equations for a full adder are:

Sum (S) = A ⊕ B ⊕ Cin
Carry (Cout) = (A·B) + (B·Cin) + (A·Cin)

In a 4-bit Ripple Carry Adder:

Four full adders are connected in series.
Each adder handles one bit of the input numbers.
The carry propagates (ripples) from the least significant bit (LSB) to the most significant bit (MSB), which may introduce delay.

Procedure:-
1. Open Logisim and create a new circuit.
2. Place input pins for two 4-bit binary numbers (A3–A0 and B3–B0).
3. Place an input pin for the initial carry (Cin), usually set to 0.
4. Construct a Full Adder using XOR, AND, and OR gates:
    i. Use XOR gates for sum calculation.
    ii. Use AND and OR gates for carry generation.
5. Replicate the full adder circuit four times to represent 4 bits.
6. Connect the carry output (Cout) of each full adder to the carry input (Cin) of the next higher-order adder.
7. Connect output pins or LEDs to observe the sum outputs (S3–S0) and final carry (Cout).
8. Provide different binary inputs and observe the resulting sum and carry.
9. Verify the outputs with expected binary addition results.

Result:-
The 4-bit Ripple Carry Adder was successfully implemented in Logisim. The circuit correctly performed binary addition for all tested input combinations, producing accurate sum and carry outputs.

Conclusion:-
The experiment demonstrated the working of a Ripple Carry Adder and the concept of carry propagation in multi-bit addition. Logisim effectively facilitated the design and simulation, helping to visualize how individual full adders combine to perform binary addition.