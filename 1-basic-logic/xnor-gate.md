# XNOR Gate



### First solution

A XNOR gate is simply the negation of a XOR gate.
We get therefore the following circuit:

![](xnor-gate-1.png)



### Second solution

Using De Morgan’s Laws, we find that
$$
  \mathtt{XNOR}(p_1, p_2)
  =
  ¬ \mathtt{XOR}(p_1, p_2)
  =
  ¬ ( (¬p_1 ∧ p_2) ∨ (p_1 ∧ ¬p_2) )
  =
  (p_1 ∨ ¬p_2) ∧ (¬p_1 ∨ p_2)
$$
We can therefore express a XNOR gate in terms of two NOT gates, two OR gates, and one AND gate:

![](xnor-gate-2.png)
