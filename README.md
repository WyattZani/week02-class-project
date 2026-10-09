# Week 2 Class Project — Ohm's Law Calculator

## Purpose
Reads a voltage and a resistance from the terminal and prints the resulting current using Ohm's law, I = V / R.

## Input / Output Contract
**Input:** two numbers on standard input — a voltage in volts, then a resistance in ohms.

**Output:**
- On success: `Current: <value> A`
- If either value is not numeric, or the resistance is zero or negative: `Invalid input`

### Examples
| Input | Output |
|---|---|
| `12 4` | `Current: 3 A` |
| `12 0` | `Invalid input` |
