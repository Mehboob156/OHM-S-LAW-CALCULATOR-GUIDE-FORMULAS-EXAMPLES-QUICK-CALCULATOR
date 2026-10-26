OHM'S LAW CALCULATOR GUIDE: FORMULAS, EXAMPLES & QUICK CALCULATOR

Find voltage, current, resistance and power from any two known values.
Open the Ohm Law Calculator: https://ohmlawcalculator.com/


QUICK OHM'S LAW CALCULATOR

Enter any two of voltage (V), current (A), resistance (Ω) or power (W) to find the other two. For unit conversion, step-by-step solutions and the interactive formula wheel, use the full Ohm Law Calculator: https://ohmlawcalculator.com/


OHM'S LAW FORMULAS

Ohm's law states that current through a conductor is proportional to voltage and inversely proportional to resistance.

Voltage (V): V = I × R, V = P / I, V = √(P × R)
Current (I): I = V / R, I = P / V, I = √(P / R)
Resistance (R): R = V / I, R = V² / P, R = P / I²
Power (P): P = V × I, P = I² × R, P = V² / R

Worked example: a 9 V battery across a 470 Ω resistor gives I = 9 / 470 = 0.01915 A (19.15 mA). Power: P = 9 × 0.01915 ≈ 0.17 W.

You can check any combination with the Ohm's Law Calculator, which shows each step: https://ohmlawcalculator.com/


SERIES AND PARALLEL CIRCUITS

Series: current is the same everywhere. R_total = R1 + R2 + R3
Parallel: voltage is the same across every branch. 1/R_total = 1/R1 + 1/R2 + 1/R3
Two resistors in parallel: R_total = (R1 × R2) / (R1 + R2)

For mixed networks, reduce each series or parallel section first, then apply Ohm's law to the total.

AC and DC: Ohm's law applies directly to resistive loads in both. For AC, use RMS values. Circuits with inductors or capacitors need impedance (Z) instead of plain resistance.

Voltage drop: V_drop = I × R_wire. A 12 V circuit drawing 10 A through 0.1 Ω of wire loses 1 V, leaving 11 V at the load. Keep drop under about 3% for most branch circuits.


LED RESISTOR CALCULATION

R = (Vs − Vf) / I

Example: 9 V supply, red LED (Vf = 2 V), 15 mA target. R = (9 − 2) / 0.015 = 467 Ω, so use the next standard value, 470 Ω.

Check the result with the Ohm Law Calculator for LED circuits before building: https://ohmlawcalculator.com/


VOLTAGE DIVIDER

Two series resistors give a lower output voltage at the midpoint.

Vout = Vin × R2 / (R1 + R2)

Example: Vin = 12 V, R1 = 1 kΩ, R2 = 2 kΩ gives Vout = 8 V.

Test other resistor pairs with the Voltage Divider Calculator: https://ohmlawcalculator.com/


RESISTOR COLOR CODE

4-band: two digits, multiplier, tolerance.
5-band: three digits, multiplier, tolerance.
6-band: same as 5-band plus temperature coefficient.

Read from the band closest to a lead. To decode any resistor, use the Resistor Color Code Calculator: https://ohmlawcalculator.com/


POWER UNITS AND LIMITS

1 hp ≈ 746 W. 1 kW ≈ 1.341 hp. 1 W ≈ 3.412 BTU/hr.

Ohm's law holds for ohmic conductors at constant temperature. It does not describe diodes or transistors, and resistance shifts as components heat up. Always pick a resistor wattage rating above the calculated power.


FAQ

What does an Ohm's law calculator do?
It takes any two of voltage, current, resistance and power and returns the other two.

How do I calculate amps?
Divide voltage by resistance: I = V / R. Or divide power by voltage: I = P / V.

How do I calculate resistance?
R = V / I. If you know power instead, use R = V² / P.

How do I calculate power?
P = V × I, or P = I² × R, or P = V² / R.

Does Ohm's law work for AC?
Yes, for resistive loads using RMS values. Reactive loads need impedance.

Does it work for LEDs and speakers?
LEDs need a series resistor sized with R = (Vs − Vf) / I. Speakers are only approximated, since impedance changes with frequency.

Can it find voltage drop?
Yes. Multiply current by wire resistance: V = I × R.


MORE TOOLS

Ohm Law Calculator: https://ohmlawcalculator.com/
Voltage Divider Calculator: https://ohmlawcalculator.com/
Resistor Color Code Calculator: https://ohmlawcalculator.com/


Educational use only. Verify ratings before building real circuits.
OhmLawCalculator.com: https://ohmlawcalculator.com/
