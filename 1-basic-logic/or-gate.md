# OR Gate

We know from De Morgan’s Laws that
$$
  ¬ (p_1 ∨ p_2) = ¬ p_1 ∧ ¬ p_2 \,,
$$
and therefore
$$
  p_1 ∨ p_2 = ¬ (¬ p_1 ∧ ¬ p_2) \,.
$$
In other words,
$$
  \mathtt{OR}(p_1, p_2)
  =
  \mathtt{NOT}( \mathtt{AND}( \mathtt{NOT}(p_1), \mathtt{NOT}(p_2) ) )
  =
  \mathtt{NAND}( \mathtt{NOT}(p_1), \mathtt{NOT}(p_2) ) \,.
$$
We thus arrive at the following circuit:

![](or-gate.png)
