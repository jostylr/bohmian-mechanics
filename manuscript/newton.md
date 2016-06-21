# Classical Limit

It is possible to analyze the circumstances that lead to classical-like trajectories in Bohmian mechanics.

One of the nice features of this analysis is that it very much shows the strength of Bohmian mechanics: waves can be waves and particles can be particles. We do not need a spread out wave to become a wave packet traveling classically; the trajectory itself is picking out the effective wave packet.

## Setting up the Classical Limit

We have trajectories in Bohmian mechanics. The simplest question is, under what conditions are these trajectories approximately classical?

That is perhaps a little too simple. One imagines that a single particle, such as an electron, will not move classically. But that perhaps a grouping of such particles, say a stone, will move classically.

Thus, the first step is to change coordinates to a center of mass coordinate, `X`$, and internal relative coordinates of all of the other particles, `Y`$.

This allows a splitting of the Hamiltonian and the effective potential acting on `X`$ is where one part of the conditions will arise. This is similar to Ehrenfest’s theorem of standard quantum mechanics.

With this setup, we can then investigate when the path `X(t)`$ will be classical.

It is quite acceptable to have an initial (very short) period of time in which there is quantum behavior that relaxes into classical behavior.

THE EMERGENCE OF CLASSICAL BEHAVIOR
There are several steps to the classical limit, conceptually. The first is to establish the behavior for a suitable class of wave functions. The wave functions are, in particular, those of the form `\psi(X) \phi(Y)`$ with `\psi`$ a wave packet of wave length `\lambda`$. Then our condition is that `V(X)`$, the effective (classical) external potential, should vary slowly relative to the wave length `\lambda`$. In particular, what one seems to need is 

```$
\lambda \ll  \sqrt{\frac{|V^{\,\,\prime}|}{|V^{\,\,\prime \prime \prime}|}} = L(V)
``` 
This is derived from the Ehrenfest 
```$
m\langle \ddot{X} \rangle = \langle -\nabla V(X(t)) \rangle
``` 
and wanting to make the assumption that 
```$
- \langle \nabla V(X(t)) \rangle \approx -\nabla V(\langle X(t)\rangle)
```

So the classical limit is somewhat giving us a condition for good initial wave functions. This might first seem a little useless since wave functions do not evolve into wave packets. Or do they in some sense?

So the next steps are to argue that a broader class of wave functions will relax to locally look like appropriate wave packets. So one does that. What kind of condition might be placed on the wave function? Well, one could use the mean kinetic energy, 
```$
E_{\mathrm{kin}} (\psi) = \langle \psi,  -\frac{\hbar^2}{2m} \nabla_x^2 \psi \rangle
``` 
to generate a suitable wave length: 
```$
\lambda (\psi) = \frac{h}{\sqrt{2m E_{\mathrm{kin}} (\psi)}}
```

The claim is that under the condition 
```$
\lambda(\psi) \ll L(V)
```
we have first the wave evolution spreading the wave function out under the direction of the kinetic term,  quickly leading to a locally plane wave function. And then, this local plane wave has local classical motion. And the particle rides the wave, thus looking classical.

## On Classical Crossing

One little problem is that classical trajectories, being second order, can cross each other in configuration space. This does not happen in Bohmian mechanics. And such situations ought to arise. Thus classical motion should not work.

But then there is decoherence. So at first, the wave is crazy. Then it relaxes. Then it starts to come back together, but by that time, it is entangled with the environment or even with its own internal degrees of freedom. So the waves that are drawn back to each other classically miss each other as these waves are on configuration space and the other coordinates of the configuration have separated them.

Which wave is relevant? The one in which the actual configuration is located. It is this which gives the wave plus particle combination such power to make everything work out just right.

# References

[Seven Steps Toward a Classical World](http://arxiv.org/abs/quant-ph/0112005)
by Valia Allori, Detlef Dürr, Shelly Goldstein, Nino Zanghí, and references therein.