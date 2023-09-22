# Second Tick

The given truth table looks as follows:

![](second-tick-truth-table.png)

The output is supposed to be false whenever the first input is false.
We can ensure this property by taking an AND with the first input:

![](second-tick-1.png)

If the first input is true, then the output is supposed to be the complement of the second input.
We therefore negate the second input before connecting it to the AND gate.

![](second-tick-2.png)
