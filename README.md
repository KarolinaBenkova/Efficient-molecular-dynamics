## Efficient Molecular Dynamics with High Accuracy
(Group project for the course Research Skills for Computational Applied Mathematics)

There exist numerous numerical integration methods for solving the Hamiltonian systems modeling molecular dynamics. Although energy is a conserved quantity of a Hamiltonian system that is not conserved exactly during discretization, symplectic integrators are accurate to some order with respect to preserving energy invariance. A prominent symplectic integrator, the Störmer-Verlet method, is conventionally applied towards molecular dynamics problems, but has a relatively low (second) order of accuracy. The Python notebooks and the report in this repository are concerned with making comparisons with this method to other numerical integration schemes for solving Hamiltonian systems: the Takahashi-Imada integrator and its simplified non-symplectic version, along with the Suzuki-Yoshida method.

The methods are applied to various problems of increasing complexity - harmonic oscllators, pendulum and pendulum systems, and a model of three (trimer) and 12 atoms. The implementation of the numerical integrators and the comparison of their energy oscillations can be found in the corresponsing Python notebooks.

## Authors
Karolína Benková, Emily McClung, Danner Morrison, and Yichen Su
