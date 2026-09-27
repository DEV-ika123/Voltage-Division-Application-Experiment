# Voltage Division Application Experiment

## Objective

To apply voltage division principles to a series resistor circuit and verify the calculated current and voltage values using Tinkercad simulation.

## Circuit

The circuit consists of:

- 9V power supply
- 1kΩ resistor
- 3kΩ resistor

Connection:

9V → 1kΩ → 3kΩ → GND

## Concept

For resistors connected in series:

- The same current flows through all resistors.
- Total resistance is the sum of the individual resistances.
- The supply voltage divides across the resistors according to their resistance values.

## Design Calculation

### Total Resistance

R_total = 1kΩ + 3kΩ

R_total = 4kΩ

### Circuit Current

I = V / R

I = 9V / 4kΩ

I = 2.25mA

### Voltage Across 1kΩ

V_1k = I × R

V_1k = 2.25mA × 1kΩ

V_1k = 2.25V

### Voltage Across 3kΩ

V_3k = I × R

V_3k = 2.25mA × 3kΩ

V_3k = 6.75V

### Voltage Check

2.25V + 6.75V = 9.00V

Therefore, the calculated voltage drops add up to the supply voltage.

## Simulation Results

| Parameter | Calculated | Tinkercad |
|---|---:|---:|
| Supply Voltage | 9V | 9.00V |
| Circuit Current | 2.25mA | 2.25mA |
| Voltage across 1kΩ | 2.25V | 2.25V |
| Voltage across 3kΩ | 6.75V | 6.75V |

## Observation

The same current flows through both series resistors, but the voltage drop is different.

The 3kΩ resistor has three times the resistance of the 1kΩ resistor, so it has three times the voltage drop.

## What I Learned

- How voltage divides across series resistors.
- How to calculate current using total resistance.
- How to calculate individual voltage drops using Ohm's Law.
- How to verify theoretical calculations using simulation.
- The relationship between resistance and voltage drop in a series circuit.

## Engineering Lesson

Voltage division is an important circuit technique used in applications such as voltage sensing, signal conditioning, and biasing.

## Tools Used

- Tinkercad Circuits
- Ohm's Law
- Digital Multimeter
