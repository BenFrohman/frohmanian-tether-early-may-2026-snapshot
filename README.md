# NS_Millennium_Proof — Frohmanian Symplectic Tether (May 28 2026 Snapshot)

**Proof of Global Smoothness for the 3D Incompressible Navier–Stokes Equations**  
**The Frohmanian Symplectic Tether Theorem**

**Author:** Benjamin Stanley Frohman (@Frohmanian / Bit21)  
**Copyright (c) 2026 Benjamin Stanley Frohman. All rights reserved.**

This is a standalone archive of the early May 2026 Lean 4 formalization snapshot (corresponding to the v2026.05.28-historical tag / complete_implementation_2026-05-28 in the main repo).

## Key Claim (as of this snapshot)
The repository presents the complete formalization of the Frohmanian Symplectic Tether framework as resolving global regularity (smoothness) of 3D incompressible Navier–Stokes solutions. The main theorem in Modules/GlobalRegularity.lean asserts unconditional global existence and smoothness for smooth, divergence-free, finite-energy initial data.

Later public Zenodo notes and the current main branch of NS_Millennium_Proof refined this to a conditional geometric reduction with named open estimates, explicit disclaimers that it is not a completed Clay resolution, and retirement of several closing paths (e.g., degeneracy leaves the equation classical; plus-weight produces a positive source rather than a sink).

## Structure (from historical snapshot)
- ForMathlib/NS/Tether.lean — geometric definitions, TetherKernel, three conditions
- Modules/GlobalRegularity.lean — main unconditional theorem
- Modules/SymplecticTether.lean, TetheredLyapunov.lean, Uniqueness.lean, etc.

See the original repo history for full files. This archive preserves the early optimistic claim for provenance.
