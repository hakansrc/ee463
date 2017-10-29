

**EE 463 PROJECT#1**

***“Single Phase Diode Rectifiers”***

*Throughout this homework, assume Turkish grid with 400 V l-l voltage
and 50 Hz frequency. When a single-phase diode rectifier is mentioned,
it is energized with a phase and neutral connection.*

***Hint:** When you need to find a commercial product, you can search
the database of “Digikey”, which is a big retailer for electronic
components, from*
[**https://www.digikey.com/**](https://www.digikey.com/) *. Other big
retailers are Farnell and Mouser.*

***Important:** While documenting your simulation results, it is often
necessary to make visual arrangements on the graph (zoom in/out, axis
scales, background color, markers etc..). When plotting a periodic
signal, a few repetitions of the full period is enough, i.e. do not plot
a 50 Hz waveform for several seconds as it makes no sense. Unless it is
stated otherwise, document only the steady state values.*

**1)** Simulate a single-phase diode rectifier feeding a resistive load
of R = 100 Ω. As the step size for the simulation, try 1.5 msec, 10 µsec
and 1 µsec. Compare the results and comment on the differences. What is
the importance of step size in a digital simulation environment?

**2)** Simulate a single-phase diode rectifier for the following loads;

- A resistive load of R = 50 Ω

- An RL load of R = 50 Ω , L = 330 µH

- An RL load of R = 50 Ω , L = 1 mH

**2.1.** Plot the output voltage waveforms at steady state and obtain
the average value of the output voltage and THD of the line current.
Compare the results and comment on the differences.

**2.2.** Choose a commercial diode suitable for the operation described
in the question. Find both a discrete diode and a single phase diode
rectifier module. State their product codes and provide their
datasheets. Make a comparison between these two possible choices (making
a rectifier from single diodes or using a rectifier module).

**2.3.** Assume an RC loaded rectifier with R=100 Ω. Find the required
capacitance value which yields an output voltage ripple smaller than 20%
of the average output voltage. Choose also a commercial capacitor
suitable for that circuit. *Hint: Among different types of capacitors,
search in the “aluminum electrolytic capacitors” category.* State the
product code and provide its datasheet.

**2.4.** Repeat the R = 50 Ω , L = 330 µH case with a line inductance of
L<sub>S</sub> = 1 mH and comment on the differences.

**2.5.** Consider the case depicted in Figure 5.25 of your textbook.
Assume the load resistance R = 25 Ω, and the line inductances
L<sub>S1</sub> = L<sub>S1</sub> = 600 µH. Draw the voltage at the point
of common coupling (PCC) and comment on the waveform.

**3)** Consider the case depicted in Figure 1. There are three
single-phase diode bridge rectifiers and they are fed by phase to
neutral voltages. Each rectifier feeds its own RC load of R = 200 Ω , C
= 470 µF. Line inductances are L = 600 µH.

**a)** Find the PF and THD of input current. Plot the waveforms for
Phase A current, neutral wire current and “Diode Bridge 1” output
voltage.

**b)** Find rms values of line currents and neutral current. Comment on
the results.

**c)** Repeat for L<sub>S</sub> = 0. Comment on the results.

![](media/image1.png)

***Figure 1.** Single-phase diode rectifiers operated from a three-phase
grid with neutral connection.*
