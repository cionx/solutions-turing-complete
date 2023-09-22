# XOR Gate



### First solution

We can express a XOR gate via
$$
  \mathtt{XOR}(p_1, p_2)
  =
  (p_1 ∧ ¬p_2) ∨ (¬p_1 ∧ p_2) \,.
$$
This formula leads to the following circuit:

![](xor-gate-1.png)



### Second solution

We need the following output:
```
Input 1   0 1 0 1
Input 2   0 0 1 1
-----------------
Output    0 1 1 0
```
Looking through the already-constructed gates, we see that the NAND gate and OR gate have the following outputs:
```
Input 1   0 1 0 1
Input 2   0 0 1 1
-----------------
NAND      1 1 1 0
OR        0 1 1 1
```
The desired output is the entrywise product of the output of the NAND gate with the output of the OR gate.
This kind of entrywise product can be computed with an AND gate.

These observations lead to the following circuit:

![](xor-gate-2.png)
