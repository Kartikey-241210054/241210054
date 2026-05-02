Aim:-
To design and simulate an 8×1 Multiplexer and an 8×3 Encoder using Logisim software and verify their functionality.

Theory:-
A Multiplexer (MUX) is a combinational circuit that selects one of many input signals and forwards it to a single output line based on select inputs. An 8×1 MUX has 8 input lines, 3 select lines, and 1 output. The select lines determine which input is connected to the output.

The Boolean expression of an 8×1 MUX is a combination of AND, OR, and NOT operations controlled by select lines.

An Encoder is a combinational circuit that converts multiple input lines into a smaller number of output lines. An 8×3 encoder has 8 input lines and produces a 3-bit binary output corresponding to the active input line. It assumes that only one input is active at a time.

Procedure:-
1. Open Logisim and create a new circuit.

For 8×1 Multiplexer:

2. Place 8 input pins representing data inputs (I0 to I7).
3. Place 3 input pins for select lines (S0, S1, S2).
4. Implement the circuit using logic gates (AND, OR, NOT) or directly use the MUX component from the library.
5. Connect inputs to the MUX according to select line combinations.
6. Attach an output pin or LED to observe the result.
7. Change select line values and verify that the corresponding input is routed to the output.

For 8×3 Encoder:

8. Place 8 input pins (D0 to D7).
9. Place 3 output pins (Y0, Y1, Y2).
10. Design the encoder using logic gates based on Boolean expressions:

Y2 = D4 + D5 + D6 + D7
Y1 = D2 + D3 + D6 + D7
Y0 = D1 + D3 + D5 + D7

11. Connect the circuit accordingly.
12. Provide one active input at a time and observe the binary output.
13. Verify outputs for all valid input conditions.


Result:-
The 8×1 Multiplexer successfully selected one input out of eight based on the select lines. The 8×3 Encoder correctly converted the active input line into its corresponding 3-bit binary output.

Conclusion:-
The experiment demonstrated the design and working of combinational circuits using Logisim. The implementation of the 8×1 MUX and 8×3 Encoder helped in understanding data selection and encoding mechanisms, reinforcing theoretical knowledge through practical simulation.