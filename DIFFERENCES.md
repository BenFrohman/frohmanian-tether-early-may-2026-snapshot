# Differences from Later Zenodo / Current Public Versions

## Early May 2026 Snapshot (this archive)
- README and GlobalRegularity.lean present an **unconditional** global regularity theorem via the Frohmanian Symplectic Tether.
- Claims the tether kernel (projected bilinear correction satisfying three geometric conditions) produces controllable negative feedback that prevents singularity formation.
- Main theorem asserts existence of global smooth solution for any smooth divergence-free finite-energy initial data.
- Some packaging uses `sorry` (energy / viscosity assumptions), but the overall claim is that the framework resolves the Clay problem.

## Later Public Records (Sept 2026 Zenodo 10.5281/zenodo.22240168 and subsequent)
- Explicit geometric reduction: degeneracy of the tether pairing leaves vorticity transport classical (no modification of the unmodified NS equation).
- Projected kernel is real symmetric bilinear form, not an antisymmetric Poisson correction.
- Plus-weight density produces a **positive** sextic source, not a sink that would close a Riccati inequality.
- One-point Young at viscous scale recovers Beale–Kato–Majda rather than a uniform Hölder modulus on the direction field ξ.
- Isolates a named remaining estimate (Definition 7.1: Hölder-½ on {r ≥ Ω}) whose verification would imply T*=∞ by classical Constantin–Fefferman / Beirão da Veiga–Berselli.
- Strong disclaimers: “not a proof of global regularity and not a blow-up example.”
- Current main branch of NS_Millennium_Proof further makes the tether theorem conditional on an open hypothesis (and has proven some versions vacuous).

## Summary of Evolution
The May snapshot recovers the early optimistic architecture in which the tether is presented as forcing a closing negative feedback. The Zenodo reconstructions (after the perceived loss) and subsequent formalizations refined this into an honest conditional reduction that retires the false closing paths and documents the remaining open geometric estimate. They are continuous developments of the same coadjoint-orbit program, not identical copies.
