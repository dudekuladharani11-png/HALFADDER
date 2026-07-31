# Half Adder using Verilog

A simple Half Adder implemented in Verilog HDL.

## Truth Table

| A | B | Sum | Carry |
|---|---|-----|-------|
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

## Logic Equations

- Sum = A XOR B
- Carry = A AND B

## Files

- `half_adder.v` - Half Adder design
- `half_adder_tb.v` - Testbench
- `README.md` - Project documentation

## Simulation

Compile:
```bash
iverilog -o halfadder half_adder.v half_adder_tb.v
```

Run:
```bash
vvp halfadder
```

## Expected Output

```
A B | Sum Carry
----------------
0 0 | 0 0
0 1 | 1 0
1 0 | 1 0
1 1 | 0 1
```
## Author Name
  D.Dharani