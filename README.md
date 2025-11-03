# 3T-DRAM

This project demonstrates the design and simulation of a 3-Transistor (3T) DRAM cell using LTspice.
The simulation focuses on performing and verifying read ‘0’, read ‘1’, write ‘0’, and write ‘1’ operations, while analyzing the voltage behavior at the storage node to confirm correct memory operation.

## Working Principle
The 3T DRAM cell consists of three NMOS transistors:
- Two access transistors used for reading and writing data.
- One storage transistor that holds the charge representing a data bit.

During the simulation:
- Write operations charge or discharge the storage node.
- Read operations sense the voltage at the node without disturbing the stored data.
- The storage capacitor voltage is monitored to verify data retention characteristics.

## Software requirement
- LTspice XVII

## Simulation Details
- Simulated using LTspice XVII.
- Implemented custom pulse signals for bitline and wordline control.
- Observed transient waveforms to study charging/discharging cycles.
- Verified correct logic transitions for read/write operations.
