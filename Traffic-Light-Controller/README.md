# Traffic Light Controller

# Overview
This project implements a four-way traffic light controller using Allen-Bradley PLC Ladder Logic in TLP LogixPro Simulator.

# Software used
- RSLogix 500
- TLP LogixPro Simulator

# PLC Instructions Used
- XIC - examine if closed
- SQO - sequencer output
- OTE - output energize

## Inputs
| Address | Description |
|---------|-------------|
| I:1/0 | Start Switch |

## Outputs
| Address | Description |
|---------|-------------|
| O:2/0 | Green 1 |
| O:2/1 | Green 2 |
| O:2/2 | Green 3 |
| O:2/3 | Green 4 |
| O:2/4 | Yellow 4 |
| O:2/5 | Yellow 3 |
| O:2/6 | Yellow 2 |
| O:2/7 | Yellow 1 |
| O:2/8 | Red 1 |
| O:2/9 | Red 2 |
| O:2/10 | Red 3 |
| O:2/11 | Red 4 |
