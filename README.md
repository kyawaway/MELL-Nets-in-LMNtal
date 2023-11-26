# MELL-Nets-in-LMNtal

Encoding of MELL(Multiplicative Exponential Linear Logic) cut-elimination into [LMNtal](https://www.ueda.info.waseda.ac.jp/lmntal/index.php).

This is the part of the presentation at [APLAS2023](https://conf.researchr.org/details/aplas-2023/src-and-posters/4/-Non-SRC-Encoding-MELL-Cut-Elimination-into-a-Hierarchical-Graph-Rewriting-Language).

### demo

Visualizing the cut-elimination (corresponding to $\beta$-reduction) of a net obtained from a simply-typed $\lambda$ term: $(\lambda f: n \to n . \lambda x: n . f x)(\lambda x : n . x)$ by using our LMNtal visual tool:

![demo](/fig/demo.gif)

The state space of this reduction:

![demo](/fig/state.png)
