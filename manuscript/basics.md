# The Minimum Bohmian Basics

In the rest of this part of the book, we will go over routine quantum mechanics from a Bohmian perspective. In order to have this make sense, there are a few basic ideas that we need to accept. The later parts of the book will go into more detail of the meaning and reason for these deep aspects of Bohmian mechanics, but we shall start by just using them. 

## Particles

This is a theory about particles with positions. If a particle exists, it has a position. That is what we mean by a particle. 

This needs to be accepted as a fundamental starting point of the theory. The goal of the theory is to describe the motion of those particles in space-time. 

## Configuration Space

In standard quantum mechanics, there is a habit to think of the wavefunction as equally representable in any convenient basis. It is thought of as just an element in an abstract Hilbert space that is built out of some kind of physically relevant machinery. 

In Bohmian mechanics, this is not true. Wavefunctions are functions on the configuration space of the particles. For the Schrödinger equation, they must be differentiable in order to provide the velocity field for the Bohmian particles.

So we need to be comfortable with `\psi(q_1, q_2, q_3, \ldots, q_n)`$ as something fundamental. The Fourier transform of `\psi`$ may be helpful in solving the equations, but it is not relevant in the formulation of the theory. Ultimately, we want a velocity field on configuration space.  

The wavefunctions are also elements of the usual Hilbert space of square-integrable wavefunctions. Much of the analysis of the theory relies on it. While presumably one could explore other functions, the analysis becomes less certain and there seems to be no physical reason to pursue it. 

## Wavefunction of a Subsystem

In typical quantum presentations, small systems are presented that end up getting entangled. But fundamentally, there are no small systems. There is only the universal wavefunction governing the whole of the universe's particles. This is what is in the theory itself. 

Now it happens, as we will explain when discussing the full formalism, that Bohmian mechanics has the property that there are situations in which it can be reasonable to approximate the evolution of a set of particles by a wavefunction on that smaller configuration space evolving according to its own Schrödinger equation. 

While this may seem similar to classical mecahnics where, say, the gravitational force of the fly on the apple can be ignored when computing the motion of the apple falling towards the ground, it is, in fact, quite different. Classically, the ideas was that the force on the apple is a sum of all these different forces acting on it and most of those forces are very negligible. 

In Bohmian mechanics, there is no such clear separation from the start. Indeed, the full extent of the wavefunction cannot be approximated in any meaningful way in terms of subsystems.

What is the key component, and ultimately is the source of the apparent collapse of the subsystem wavefunction, is that the environment serves as a localization for a subsystem, whenever it applies. That is, we get subsystems by doing a partial evaluation of the wavefunction. 

So in some of our considerations, we need to justify why we have a subsystem rather than how a system gets entangled. 

That is `\Psi`$, the universal wavefunction is preeminent and `\psi`$, the subsystem wavefunction is what needs to be deduced. 


## Probability

The probability of finding a configuration of a subsystem with wavefunction
`\psi`$ is given by the density `|\psi|^2 (q) dq`$.  From this, all the
results of standard quantum mechanics follows. 

The important point of note is that this is not an assumption. This is a
deduction based on typicality arguments. That is, for a typical configuration
of the universe, an appropriate subsystem will have this property that we call
the Quantum Equilibrium Hypothesis. 

Typicality is measured with respect to the density `|\Psi|^2`$. This needs
explaining as we do later. But for now, we take it as a basic assumption the
QEH holds. 

## Operators

Along with subsystems having the correct probability, we also have standard quantum Observables. These are mathematically represented, in its simplest form, as self-adjoint linear operators acting on the Hilbert space of wavefunctions. 

The standard rules imply that wavefunctions collapse into eigenstates of those operators when a corresponding measurement is made. These rules and an understanding of why this occurs is made explicit in an analysis of Bohmian mechanics as we do later in the book. 

For now, all the usual rules do apply though we will generally be concerned with the evolution of the subsystem rather than a measurement of it. The Hamiltonian, while it is an Observable, has a special role not because of that, but rather because it is the heart of the evolution. 

## The Equations

guiding equation, schrodinger equation,  and dirac-bohm model. 

