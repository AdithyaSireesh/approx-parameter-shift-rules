# Approx Parameter Shift Rules

In this work, we tackle one of the fundamental areas in Quantum Machine Learning: gradient based
optimization of variational quantum circuits using the parameter shift rules. We go through the
existing literature on the shift rules and its variants (Two-term [Mitarai et al. (2018)], Four-term, Gate
Decomposition [Crooks (2019)], Stochastic [Banchi and Crooks (2021)] and General Parameter Shift
Rules [Wierichs et al. (2022)]) which are used based on the specific forms of the Unitary Generators
that make up the parametrised gates in the ansatz. We also show proofs for the two term and general
parameter shift rules. Finally, to tackle the computational costs of the shift rules, we propose and run
three toy experiments, and propose new methods to approximate the analytic gradients (from the
shift rules), and even find that in two of the three cases our approximations converge to the solutions
much faster than the analytic gradients from the shift rules.
