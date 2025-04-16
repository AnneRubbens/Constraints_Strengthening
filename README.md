# Constraints_Strengthening

This repository is a companion to reproduce all examples of the work:

> [1] Anne Rubbens, Julien M. Hendrickx, Adrien Taylor. "A constructive approach to strengthen algebraic descriptions of function and operator classes."

Date:    February 2025

Version: February 2025

#### Folder organization & files

(1) [`Constrained-strenghtening procedure`](One-Point_Strengthenings/): Mathematica notebooks containing
- detailed computations of [1, Section 2.5]: [`Convex smooth functions`](Examples/Convex_Smooth_Functions.nb),
- detailed computations of [1, Section 3.1]: [`Smooth functions with Lojasiewicz condition`](Examples/Smooth_Lojasiewicz_Functions.nb),
- detailed computations of [1, Section 3.2]: [`Block-smooth convex functions`](Examples/Blockwise_Smooth_Convex_Functions.nb)
- detailed computations of [1, Appendix G]: [`Uniformly convex and Holder smooth functions`](Examples/Uniformly_Convex_Functions.nb)
- detailed computations of [1, Section 3.3]: [`Monotone Lipschitz operators`](Examples/Monotone_Lipschitz_Operators.nb)
- detailed computations of [1, Appendix F]: [`Strongly monotone cocoercive operators`](Examples/Monotone_Cocoercive_Operators.nb)

(2) [`SOS formulation`](SOS_Formulations/): Mathematica notebooks containing
- detailed computations of [1, Proposition 3.4]: [`Smooth functions with Lojasiewicz condition`](SOS_Formulations/Smooth_Lojasiewicz_Functions_SDP.nb),
- detailed computations of [1, Proposition 3.9]: [`Block-smooth convex functions`](SOS_Formulations/Blockwise_Smooth_Functions_SDP.nb)
- detailed computations of [1, Proposition 3.15]: [`Monotone Lipschitz operators`](SOS_Formulations/Monotone_Lipschitz_Operators_SDP.nb)
- detailed computations of [1, Proposition F3]: [`Strongly monotone cocoercive operators`](SOS_Formulations/Monotone_Cocoercive_Operators_SDP.nb)

(3) [`PEPit examples`](PEPit/):
- PEP application: a block-coordinate descent method analyzed with conditions from [1, Proposition 3.9]: [`BlockCoordinate`](PEPit/BCD.ipynb).
- PEP application: a gradient descent method analyzed with conditions from [1, Proposition 3.4]: [`GradientDescent`](PEPit/GD.ipynb).
- PEP application: optimistic gradient and extragradient analyzed with conditions from [1, Proposition 3.15]: [`OEDescent`](PEPit/OG_EG.ipynb).

#### Authors
- [**Anne Rubbens**](https://scholar.google.com/citations?user=J4J2l6oAAAAJ&hl=en&oi=ao)
- [**Julien M. Hendrickx**](https://perso.uclouvain.be/julien.hendrickx/)
- [**Adrien Taylor**](http://www.di.ens.fr/~ataylor/)

