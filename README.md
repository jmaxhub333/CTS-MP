# CTS-MP
# DC Circuit Theorem Explorer

An interactive educational web app for exploring basic DC circuit analysis. Adjust the circuit values and observe how the load voltage, current, equivalent circuit, and power transfer change.

**Live app:** [Open DC Circuit Theorem Explorer]([https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/](https://jmaxhub333.github.io/CTS-MP/))

## Project overview

This project demonstrates several core electrical engineering concepts using a resistive DC circuit. It is designed as a learning aid: users can change component values and compare the resulting circuit quantities and theorem-based analyses.

The app covers:

- Kirchhoff’s Current Law (KCL)
- Kirchhoff’s Voltage Law (KVL)
- Node analysis
- Mesh analysis
- Thevenin’s theorem
- Norton’s theorem
- Maximum power transfer

## Circuit model

The example circuit has a DC voltage source \(V_s\), a series resistor \(R_1\), and a parallel network containing \(R_2\) and the load resistor \(R_L\).

```text
       R1
 Vs ──/\/\/───● Vout
              │
         ┌────┴────┐
         │         │
        R2        RL
         │         │
 GND ────┴─────────┘
