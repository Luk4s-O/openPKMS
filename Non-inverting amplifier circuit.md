Non-inverting [[op-amp]]s work following the op amp golden rules:

1.  The Current Rule: No current flows into the inputs of the op amp ($I+=I-=0$).
2.  The Voltage Rule: The output of the op amp attempts to ensure that the voltage difference between the two inputs is zero ($V+=V-$).

Consider a non-inverting op amp circuit where:
- The input voltage $V_{in}$ is wired to the (+) input of the op-amp
- $R_1$ is wired from ground to the (-) input and to $R_2$ 
- $R_2$ is wired from $R_2$ to the ouptut

According to the Voltage Rule, the voltage at the inverting (-) input will be the same as at the non-inverting (+) input, which is the applied voltage $V_{in}$.

The current going through $R_1$ can then be given as $$\frac{V_{in}}{R_1}$$
According to the Current Rule, the inputs draw no current, so all that current must then flow through $R_2$.

The output voltage can then be given as $$V_{out}=V_{in}+\frac{V_{in}R_2}{R_1}$$
The gain is then $$\frac{V_{out}}{V_{in}}=1+\frac{R_2}{R_1}$$
The gain will never be less than 1, so the non-inverting op amp will produce an amplified signal that is in phase with the input.