A Csound implementation of the hyperbolic tangent waveshaping virtual analog oscillator. 
The hypersaw opcode generates the tanh function as a table lookup for improved computational efficiency, generates
a sine wave and passes the sine wave signal through the function lookup table. The output is then ring modulated 
to shape the resulting square wave into a band-limited sawtooth wave.

The hypersaw is implemented from the formula process described by V. Lazzarini in the following paper:
Lazzarini, V. & Timoney, J.
 "New Perspectives on Distortion Synthesis for Virtual Analog Oscillators", 
 Computer music journal, vol. 34, no. 1, 2010, pp. 28-40.
