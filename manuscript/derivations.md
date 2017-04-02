# Derivations

Bohmian mechanics can be derived in a variety of fashions. This page details some of them.

We start in each and every case with the assumption that there are particles with positions and it is our task

## Probability Current

The way that has guided further extensions is the probabilistic insight. We want the trajectories in configuration space to be such that the quantum probability evolves along the trajectories.

A rather comprehensive way of coming up with a velocity law for various Hamiltonians is given in
[De Broglie-Bohm Guidance Equations for Arbitrary Hamiltonians](http://arxiv.org/abs/0808.0290) by  Ward Struyve and Antony Valentini.

## Symmetry

We want a law of motion that transforms correctly under Galilean transformations. By pursuing this, Bohm’s law emerges.

##  Hamiltonian Flow

Consider that a velocity field can also be viewed as a differential operator acting on a function. If we know how it operates on all functions, we know the velocity field. Consider that by viewing functions as multiplication operators in position space, we have a time evolution of that operator. Differentiate and we end up with the commutator with the Hamiltonian. Apply to the wave function, take the inner product and its real part, scale it, etc., and we end up with defining a vector field by how it operates on the various functions. That vector field is the same velocity law.

For second-order differential operators and lower, this approach works and agrees with the work of Struyve and Valentini though their work extends more.

## De Broglie Relations

We can derive Bohm’s equation the same way we derive Schrödinger’s equation. The relation
`p = \hbar k`$  for a plane wave of the form `\psi(q, t) = e^{i(k \cdot q \omega t)}`$ suggests

```$
m v = p = \hbar k = \frac{\hbar}{i} \frac{\nabla \psi}{\psi}
```

which is in fact Bohm’s equation when we take only the real part for a non-plane wave function. That’s it. Schrödinger’s equation is actually more complicated.

## Hamilton-Jacobi

By decomposing the wave function into `\psi = R e^{i S}`$, the polar form, Schrödinger’s equation becomes the continuity equation, used in the probability current, and a Hamilton-Jacobi equation with an extra potential term involving R. This is the quantum potential. This is a second-order formulation of Bohm’s equation which only gives the correct prediction if the initial velocities are given by Bohm’s equation.

This is the derivation Bohm used.

## Square-root of the Tangent Space
