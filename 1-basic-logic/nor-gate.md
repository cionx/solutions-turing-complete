# NOR Gate

The parallel level on OR gates should be done before this level.

We can implement a NOR gate in terms of an OR gate and a NOT gate via
$$
  \mathtt{NOR}(p_1, p_2)
  =
  \mathtt{NOT}( \mathtt{OR}(p_1, p_2) ) \,.
$$
We have already unlocked NOT gates, but not OR gates.
But we have seen in the parallel level on OR gates how these can be implemented in terms of NAND gates and NOT gates; one NAND gate and two NOT gates, to be precise:

![](or-gate.png)

We can therefore implement a NOR gate in terms of one NAND gate and three NOT gates:

![](nor-gate.png)
