# Super-simple overview

## One photon, one two-level system

### Resonance at rest

```
.
.                ------- E_1
.      w_p          A
.     ~~~>          |
.                   |--w_0
.                   V
.                ---x--- E_0
```

One of the most simple interactions between light and matter (aside from the fundamental QED Feynman graph) is that between a single photon of energy $\hbar\omega_p$ (and frequency $\omega_p$) and a two-level system with a resonance frequency $\omega_0 = (E_1-E_0)/\hbar$. If those frequencies match, the photon can get _absorbed_ to make the system excited.

```
.
.                ---x--- E_1
.                   A
.                   |
.                   |--w_0 = w_p
.                   V
.                ---o--- E_0
```

The excitement won't last forever though and due to a process know as _spontaneous emission_ the original photon can get emitted again in a _random direction away_, leaving the system again in its original, un-excited state.

```
.
.                ------- E_1
.                   A          w_p
.                   |         ~~~> (random direction away)
.                   |--w_0
.                   V
.                ---x--- E_0
```

But in reality, there are several assumptions not met exactly in the sentence _"One photon interacts with one two-level system at rest at exact resonance"_, and we'll go through each semantic block in this:

* There is more than "_one_ photon", leading to _stimulated emission_
* The photon could _not_ interact with the system at all, though that's trivial and thus boring
* There is more than "_one_ two-level system", leading to statistical effects, especially _temperature_
* There are more than "_two-level_"s for the system, which is actually important for a _laser_
* The system is not exactly "_at rest_" (with respect to the observer's laboratory system), see _relativistic Doppler shift_
* The interaction doesn't happen "at _exact resonance_", i.e. the photon energy does not exactly match, see _Rabi oscillations_
* The interaction could be between something else than a _photon_ and a _system_ to be precise, but that is out of scope for this document

### Resonance in motion

As described in [the Wikipedia article on the relativistc Doppler shift](https://en.wikipedia.org/wiki/Relativistic_Doppler_effect) (named after physicist Christian Doppler, though his description is only valid for non-relativistic velocities), if the light source and the system are in motion relative to each other, a frequency shift depending on the relative velocity occurs. Light is "_blue-shifted_" (or more precisely, perceived as having a higher frequency than at relative rest) when the light source and the system are moving towards each other and "_red-shifted_" (having lowered frequency).

The energetic symmetry of [resonance at rest](#resonance-at-rest)