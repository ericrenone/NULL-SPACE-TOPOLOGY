# NULL SPACE TOPOLOGY

**Phase Singularities, Entanglement Networks, and the Gravitational Architecture of Spacetime**

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone

---

> "The solid and reliable structure of space-time is due to the ghostly features of entanglement." — J. Maldacena, Institute for Advanced Study, 2013

> "Theory has long predicted that optical singularities can exhibit superluminal motion, particularly at moments close to their creation or annihilation, where their velocities can become unbounded." — Kaminer et al., Nature 651, 920–926, March 2026

> "Without these connections, all of space would atomize." — L. Susskind, Stanford University, 2015

---

## Abstract

Three results from independent lines of research — Nye-Berry topological singularity theory (1974–1978), the Maldacena-Susskind ER = EPR conjecture (2013), and the Kaminer et al. experimental confirmation of superluminal dark-point motion (2026) — converge on a single structural claim: spacetime is a null-space network. Phase singularities in any complex scalar field obey universal topological dynamics — quantized charge, pair creation/annihilation, superluminal kinematics near annihilation. Black hole event horizons are null points of the timelike Killing field, obeying the same dynamics. The ER = EPR conjecture connects all such null points through a Planckian wormhole network whose entanglement structure constitutes spatial connectivity itself.

This paper develops five consequences of this convergence that do not appear in the existing literature: (1) a Markov blanket formalism for phase singularities identifying event horizons as conditional independence boundaries, (2) a col$(F)$/ker$(F)$ decomposition of the null-point manifold separating observable from behind-horizon degrees of freedom, (3) a specific equation $\rho_{\text{DM}}(r) \propto \nabla^2 S_{\text{EE}}(r)$ proposing dark matter density as the Laplacian of entanglement entropy, (4) a reinterpretation of binary black hole mergers as Berry null-point annihilation events testable in LIGO ringdown waveforms, and (5) null-point density as an independent topological estimator of the stochastic gravitational wave background energy spectrum $\Omega_{\text{GW}}(f)$.

---

# PART I · FOUNDATIONS

---

## I. Topological Null Points: Universal Wave Singularities

A null point in a complex scalar field $\psi(\mathbf{r}, t)$ is a location where $|\psi| = 0$ and $\arg(\psi)$ is undefined. The phase winds by $2\pi q$ around each null, with topological charge

$$q = \frac{1}{2\pi} \oint_C \nabla \arg(\psi) \cdot d\mathbf{l} \in \mathbb{Z}$$

conserved exactly: null points appear and disappear only in opposite-charge pairs $(+1, -1)$. This conservation is topological — it holds in any continuous complex field independent of the underlying physics (Nye and Berry, Proc. Roy. Soc. A 336, 165–190, 1974).

Berry (J. Phys. A 11, 27–37, 1978) proved that null-point velocities diverge near pair annihilation events, with the scaling $v \propto t^{-1/2}$ as annihilation approaches. The acceleration is superluminal but does not violate relativity: null points carry no mass, no energy, and no information.

Kaminer et al. (Nature 651, 920–926, March 2026) confirmed this experimentally at the Technion Electron Microscopy Center. Using ultrafast electron microscopy, the team tracked optical phase singularities in polariton waves in hexagonal boron nitride (hBN). Twenty-nine percent of tracked null points exceeded $c$. The average superluminal speed was $\sim 1.04c$. Near annihilation events, velocities became unbounded, matching Berry's 1978 prediction.

The Technion result is universal. Kaminer's group: "Our discovery reveals universal laws of nature shared by all types of waves, from sound waves and fluid flows to complex systems such as superconductors." The topological structure — charge conservation, pair creation/annihilation, superluminal motion — follows from the mathematics of complex scalar fields, not from any specific field theory.

---

## II. Gravitational Null Points

A Killing vector field $\xi^\mu$ generates a spacetime symmetry. For stationary spacetimes, the timelike Killing field $\xi^\mu = (\partial/\partial t)^\mu$ has norm $\xi_\mu \xi^\mu = g_{tt}$. A black hole event horizon is the null surface where

$$\xi_\mu \xi^\mu = 0$$

The field that normally points "forward in time" degenerates to zero norm. The event horizon is a null point of the timelike Killing field in the same mathematical sense that an optical vortex is a null point of the electromagnetic field amplitude: both are loci where a defining field quantity vanishes and a phase-like variable becomes undefined (Hawking and Ellis, *The Large Scale Structure of Space-Time*, Cambridge, 1973).

The Kerr rotating black hole has a ring singularity at $r = 0, \theta = \pi/2$ — topologically $S^1$, a closed vortex line in spacetime (Kerr, Phys. Rev. Lett. 11, 237–238, 1963; Carter, Phys. Rev. 174, 1559–1571, 1968). This is structurally identical to a vortex ring in fluid dynamics or a phase dislocation line in optics (Nye-Berry 1974).

The topological charge of a black hole — its irreducible mass, angular momentum, and electric charge — is conserved. Black holes form and merge under the area theorem ($\delta A \geq 0$, Hawking 1971) and cosmic censorship (Penrose 1969). The surface gravity $\kappa$ at the horizon determines the Hawking temperature $T_H = \hbar\kappa / (2\pi k_B c)$ (Hawking, Commun. Math. Phys. 43, 199–220, 1975). The Bekenstein-Hawking entropy $S_{\text{BH}} = A/(4G_N\hbar)$ counts the degrees of freedom of the null surface.

---

## III. The Connected Null-Space Network

Einstein and Rosen (Phys. Rev. 48, 73–77, 1935) showed the Schwarzschild solution contains a bridge connecting two exterior regions through the black hole interior. Einstein, Podolsky, and Rosen (Phys. Rev. 47, 777–780, 1935) identified quantum entanglement as a nonlocal correlation.

Maldacena and Susskind (Fortschritte der Physik 61(9), 781–811, 2013) proposed these are the same phenomenon: **ER = EPR**. Two entangled black holes are connected by an Einstein-Rosen bridge. The entanglement entropy equals the Ryu-Takayanagi entropy:

$$S_{\text{ent}} = \frac{\text{Area}(\gamma_A)}{4G_N\hbar}$$

where $\gamma_A$ is the minimal codimension-2 bulk surface anchored to boundary region $A$ (Ryu and Takayanagi, Phys. Rev. Lett. 96, 181602, 2006).

The radical extension: all entangled systems are connected by Planckian wormholes. "Even for an entangled pair of particles, in a quantum theory of gravity there must be a Planckian bridge between them, albeit a very quantum mechanical bridge which probably cannot be described by classical geometry" (Maldacena and Susskind 2013).

Van Raamsdonk (Gen. Rel. Grav. 42, 2323–2329, 2010) demonstrated that reducing entanglement between two CFT regions causes the dual bulk spacetime to disconnect. The null-space network is not correlated with spacetime — it constitutes spacetime. Spatial connectivity is entanglement connectivity.

The network is not static. Susskind proposed that black hole interior volume grows linearly after thermal equilibrium, tracking computational complexity (Phys. Rev. D 93, 064025, 2016). The "Einstein-Rosen caterpillar" result (2025) formalized this: wormhole geometric length increases with quantum randomness of the underlying state — complexity equals geometry. The growth rate is bounded by the Maldacena-Shenker-Stanford chaos bound $\lambda_L \leq 2\pi k_B T/\hbar$ (JHEP 08(2016)106). Black holes saturate this bound — they are the fastest scramblers in nature (Sekino and Susskind, JHEP 10, 065, 2008).

---

# PART II · NOVEL CONTRIBUTIONS

---

## IV. Markov Blankets for Phase Singularities

**This section introduces a formalism not present in the Nye-Berry literature or the ER = EPR programme.**

Define the Markov blanket $B_i$ of null point $i$ as the minimal set of neighboring null points such that the future trajectory of $i$ is conditionally independent of the global field given $B_i$:

$$P\left(r_i(t + \Delta t) \mid B_i\right) = P\left(r_i(t + \Delta t) \mid \text{global field}\right)$$

The blanket state vector $s_i = \{d_{ij}, q_j, \nabla\arg(\psi)|_{r_j}\}_{j \in B_i}$ captures the distances, topological charges, and local phase gradients of blanket members. The claim is specific: the Berry $-1/2$ velocity scaling near annihilation events is fully determined by the blanket state alone, with no information leaking in from outside the blanket.

**Gravitational interpretation.** A black hole's event horizon is a causal boundary rendering the interior conditionally independent of the exterior. The Markov blanket of a black hole IS its event horizon:

$$P(\text{interior} \mid \text{horizon}) = P(\text{interior} \mid \text{universe})$$

This is the no-hair theorem in information-theoretic language. The horizon screens the bulk from the environment — the holographic principle (Susskind, J. Math. Phys. 36, 6377–6396, 1995; 't Hooft 1993) restated as conditional independence. The Ryu-Takayanagi formula computes the entanglement entropy across the Markov blanket. The Bekenstein-Hawking entropy counts the blanket's degrees of freedom.

This connects to the FERN framework's treatment of collective Markov blankets (FERN-C4): the collective Markov blanket exists as a coherent inferential unit if and only if all agents have access to the collective's blanket states. For the gravitational null-space network, this translates to a precise requirement: the ER bridge network functions as a coherent gravitational structure if and only if the entanglement across each event horizon (each blanket) is maintained. Van Raamsdonk's result — that removing entanglement disconnects spacetime — is the gravitational failure mode of the FERN blanket observability condition.

**What is new:** The application of the Markov blanket formalism to phase singularity dynamics specifically — treating each null point as an agent whose causal neighborhood is its blanket — has not appeared in the vortex dynamics, singular optics, or active inference literatures. The identification of event horizons with Markov blankets reformulates established physics (no-hair theorem, holographic principle) in a language that connects gravitational physics to the active inference programme (Friston et al., 2024; Ramstead et al., 2023).

**What remains open:** A proof that the blanket dynamics alone reproduce Berry's $-1/2$ scaling — that the conditional independence condition follows from the field equations rather than being imposed by fiat. This proof would establish the Markov blanket as a theorem of vortex dynamics rather than a conjecture. The proof strategy mirrors FERN-C1: show that the null-point dynamics can be represented as sufficient statistic updates, then apply Chentsov's theorem to establish the Fisher-Rao metric as the unique invariant metric on the blanket manifold.

---

## V. The col$(F)$/ker$(F)$ Decomposition on the Null-Point Manifold

**This section connects the TRACTUS architecture to the gravitational null-space network.**

The manifold of null-point configurations — positions, charges, and phase gradients of all null points in a field — carries a natural information metric. Construct a local Fisher information matrix $F$ from the phase gradients within each Markov blanket:

$$F_{ij} = \left\langle \frac{\partial \ln L}{\partial s_i} \frac{\partial \ln L}{\partial s_j} \right\rangle$$

where $L$ is the likelihood of the observed null-point configuration given the blanket state. The TRACTUS col$(F)$/ker$(F)$ split decomposes the tangent space:

$$\mathbb{R}^d = \text{col}(F) \oplus \ker(F), \quad \dim(\text{col}(F)) = r, \quad \dim(\ker(F)) = d - r$$

The Moore-Penrose pseudoinverse acts only on the column space:

$$F^+ g = U_r \Sigma_r^{-1} U_r^T g$$

with zero response in ker$(F)$. This is not an approximation — the ker$(F)$ component carries no Fisher information by definition, and discarding it is the Data Processing Inequality (Shannon 1948): post-processing in ker$(F)$ cannot increase the information content of the measurement.

**Gravitational interpretation:**

| Fisher Subspace | Gravitational Meaning |
|---|---|
| col$(F)$: directions with $\lambda_i > \varepsilon$ | Observable BH parameters: mass $M$, spin $J$, charge $Q$ |
| ker$(F)$: directions with $\lambda_i < \varepsilon$ | Behind-horizon interior states, screened by the Markov blanket |
| Rank crossings: $\Delta\text{rank}(F) = +1$ | Topological phase transitions: null-point pair creation or annihilation |
| Fisher trace rate $\Xi_F(t)$ | Rate of change of total observable information in the network |

The TRACTUS framework provides the computational architecture for this decomposition. The col$(F)$/ker$(F)$ split reduces the effective dimensionality from $O(d^2)$ to $O(r \cdot d)$ where $r = \text{rank}(F) \ll d$ — the same structural insight that makes natural gradient descent tractable (TRACTUS Identity 1). The CHORD Q16.16 floor $\varepsilon = 2^{-16}$ provides a hard threshold separating col$(F)$ from ker$(F)$: eigenvalues below $\varepsilon$ are exactly zero in the arithmetic, eliminating the ill-conditioning that plagues standard Fisher computations (TRACTUS Identity 2). Sherman-Morrison rank-one updates handle topological phase transitions (rank crossings) at $O(r \cdot d)$ per event (TRACTUS Identity 5).

**What is new:** The identification of col$(F)$ with observable (exterior) black hole degrees of freedom and ker$(F)$ with unobservable (interior) degrees of freedom, mediated by the Markov blanket/event horizon, connects the TRACTUS natural gradient architecture to the holographic principle. No prior work has mapped the col$(F)$/ker$(F)$ split onto the exterior/interior partition of black hole physics.

**What this does not yet provide:** A physical prediction beyond what the Ryu-Takayanagi formula already gives. The col$(F)$/ker$(F)$ decomposition becomes physically productive only when it yields predictions distinguishable from standard holographic calculations — for instance, if the Fisher trace rate $\Xi_F(t)$ at rank crossings correlates with measurable properties of black hole merger waveforms.

---

## VI. Dark Matter from Entanglement Entropy

**This section contains the paper's central speculative proposal.**

If spacetime connectivity is entanglement connectivity (Van Raamsdonk 2010), the entanglement entropy distribution across the null-space network determines the effective gravitational field at all scales. Define the entanglement entropy profile $S_{\text{EE}}(r)$ around a black hole of mass $M$ as the von Neumann entropy of the reduced density matrix inside radius $r$:

$$S_{\text{EE}}(r) = -\text{Tr}(\rho_A \log \rho_A), \quad \rho_A = \text{Tr}_B \, \rho_{\text{total}}$$

The Ryu-Takayanagi formula gives $S_{\text{EE}}(r) = \text{Area}(\gamma_r)/(4G_N\hbar)$ where $\gamma_r$ is the minimal surface at radius $r$.

**The proposal:**

$$\rho_{\text{DM}}(r) \propto \nabla^2 S_{\text{EE}}(r)$$

Dark matter density is the Laplacian of the entanglement entropy profile.

**The derivation chain.** Jacobson (Phys. Rev. Lett. 75, 1260–1263, 1995) derived Einstein's field equations from thermodynamic assumptions at local Rindler horizons, establishing a proportionality between entropy variation and gravitational potential variation: $\delta S \propto \delta \Phi$ at each causal horizon. If this proportionality extends to the entanglement entropy profile — if $S_{\text{EE}}(r) \propto \Phi(r)$ where $\Phi$ is the effective gravitational potential — then Poisson's equation $\nabla^2 \Phi = 4\pi G \rho$ gives $\rho \propto \nabla^2 S_{\text{EE}}$.

**The NFW prediction.** The Navarro-Frenk-White profile (ApJ 462, 563–575, 1996) describes the universal dark matter halo:

$$\rho_{\text{NFW}}(r) = \frac{\rho_0}{(r/r_s)(1 + r/r_s)^2}$$

with $\rho \propto r^{-1}$ at small $r$ and $\rho \propto r^{-3}$ at large $r$. The prediction: the entanglement entropy profile around a Schwarzschild black hole in asymptotically flat spacetime, computed via the generalized Ryu-Takayanagi formula (Engelhardt and Wall, JHEP 2015; Dong, JHEP 2014), produces a $\nabla^2 S_{\text{EE}}$ matching the NFW functional form, with $r_s$ and $\rho_0$ determined by $M$ and the entanglement structure of the surrounding network.

**Position relative to existing work:**

| Programme | Mechanism | Dark Matter Status | NFW Prediction |
|---|---|---|---|
| $\Lambda$CDM | Cold dark matter particles (WIMPs, axions) | Substance: new particle species | NFW from N-body simulations |
| MOND (Milgrom 1983) | Modified dynamics below $a_0 \sim 10^{-10}$ m/s$^2$ | No dark matter; modified gravity | Does not predict NFW |
| Verlinde (JHEP 2011, 2017) | Gravity from entropy gradients | Emergent: entanglement volume | Partial — derives MOND interpolation, not NFW directly |
| This work | $\rho_{\text{DM}} \propto \nabla^2 S_{\text{EE}}$ via null-space network | Emergent: entanglement Laplacian | Predicts NFW from $S_{\text{EE}}(r)$ profile — untested |

The critical distinction from Verlinde: this proposal maps entanglement entropy to dark matter density through a specific equation ($\nabla^2 S_{\text{EE}}$) that produces a density profile, not just a force law. The equation is testable by computing $S_{\text{EE}}(r)$ for a realistic galaxy.

**The unproven link.** The identification $S_{\text{EE}}(r) \propto \Phi(r)$ is suggested by Jacobson (1995) but not established for the entanglement entropy profile around a specific black hole in flat spacetime. The Ryu-Takayanagi formula gives $S_{\text{EE}} \propto \text{Area}$ (a surface quantity), not directly a potential (a volume quantity). The relationship between the area of a minimal surface at radius $r$ and the gravitational potential at $r$ is nontrivial and unproven. Without this link, the equation $\rho_{\text{DM}} \propto \nabla^2 S_{\text{EE}}$ is a conjecture with physical motivation and no quantitative support.

**The computation that would settle this:** Compute $S_{\text{EE}}(r)$ around a Schwarzschild black hole of mass $M$ in asymptotically flat spacetime using the generalized Ryu-Takayanagi formula. Take the Laplacian. Compare to NFW with $r_s$ and $\rho_0$ fit from the SPARC database ($\sim$175 galaxies with measured rotation curves and baryonic mass distributions; Lelli et al., AJ 152, 157, 2016). If the functional form matches, the equation becomes a prediction with quantitative content. If not, revise or withdraw.

---

## VII. Gravitational Wave Null Points and the Dark-Points Connection

**This section extends the Technion result to gravitational waves and proposes testable predictions for LIGO/Virgo/KAGRA.**

Gravitational waves in linearized GR are described by the complex strain $h = h_+ + ih_\times$. This is a complex scalar field satisfying all conditions for Nye-Berry theory: complex-valued, continuously varying, subject to interference. Its null points — locations where $h_+ = h_\times = 0$ simultaneously — are gravitational wave phase singularities carrying quantized topological charge.

The universality established by Nye-Berry (1974) and confirmed by Kaminer et al. (2026) guarantees that these gravitational wave null points obey the same topological dynamics as optical vortices: charge conservation, pair creation/annihilation, and superluminal motion near annihilation events.

**The novel connection.** Binary black hole mergers are null-point pair annihilation events. When two event horizons (gravitational null surfaces) collide and merge, the process is structurally identical to the optical vortex pair annihilation observed at the Technion. The gravitational wave burst at merger — the peak strain — corresponds to the Berry superluminal acceleration at the moment of annihilation. The null points of $h_+ + ih_\times$ should exhibit unbounded velocity in the $\sim$10 ms surrounding the merger peak.

This identification — the Technion dark-points result as the optical analogue of binary BH mergers, with both governed by Berry's universal null-point kinematics — has not appeared in the literature. The universality is established mathematics (Nye-Berry theorem applies to all complex scalar fields). The specific prediction (Berry $\alpha = -1/2$ scaling in LIGO merger waveforms) is new and testable.

**The deeper claim.** The superluminal motion of dark points (optical nulls) and the non-traversability of ER bridges (gravitational nulls) are two manifestations of the same topological phenomenon. Both are null — zero amplitude, zero energy, zero information. Both exhibit kinematics unconstrained by the speed of light. Both connect regions of the field without transmitting information between them. The dark points move faster than light because they are topological features, not physical objects. The ER bridges connect without transmitting because they are topological features, not physical channels. The null-space network connecting all black holes is the gravitational-scale version of the dark-point dynamics observed at the Technion — the same universal wave topology operating at $10^{-7}$ m (hBN polaritons) and $10^{26}$ m (the Hubble volume).

---

## VIII. Falsifiable Predictions

Eight predictions, ordered by proximity to current experimental capability.

**Prediction 1: Berry $\alpha = -1/2$ scaling in LIGO ringdown.** Compute $h_+ + ih_\times$ for binary BH merger events in GWTC-3/GWTC-4. Identify null points in the complex strain via time-frequency analysis. Track their velocities near the merger peak. Berry's kinematics predict $v \propto t^{-1/2}$ near annihilation. Testable with existing LIGO data, requires no new observations.

**Prediction 2: Null-point density as $\Omega_{\text{GW}}(f)$ estimator.** The number density of null points per unit time-frequency area in the wavelet-transformed SGWB should scale linearly with $\Omega_{\text{GW}}(f)$: more interference produces more null points. This provides an independent topological estimator complementing the standard cross-correlation method. Testable in LIGO O4/O5 analyses.

**Prediction 3: Charge conservation in SGWB.** Total topological charge in any compact region of the time-frequency plane should be conserved to high precision ($< 1\%$ deviation). Violations indicate non-Gaussianity or detector artifacts.

**Prediction 4: Superluminal GW null-point motion near mergers.** During the $\sim$10 ms surrounding the strain peak of a binary BH merger, the null points of $h_+ + ih_\times$ should exhibit superluminal motion — the gravitational analogue of the Technion result.

**Prediction 5: NFW from $\nabla^2 S_{\text{EE}}$.** Compute $S_{\text{EE}}(r)$ for a Schwarzschild BH in asymptotically flat spacetime via the generalized Ryu-Takayanagi formula. If $\nabla^2 S_{\text{EE}}$ matches NFW with the correct $r_s$ and $\rho_0$, dark matter is an entanglement effect. Compare to SPARC rotation curves. Requires new theory, not new observations.

**Prediction 6: Entanglement entropy bound on halo mass.** If dark matter is vacuum entanglement, the total DM mass inside radius $R$ around a BH of mass $M$ should satisfy $M_{\text{DM}}(R) \leq S_{\text{BH}} \cdot (R/r_s)$. Testable by comparing observed halo-to-SMBH mass ratios across the $M_{\text{BH}}$–$M_{\text{halo}}$ scaling relation.

**Prediction 7: SMBH connectivity and cosmic web structure.** Cross-correlate SMBH catalogs (eROSITA, JWST) with Lyman-$\alpha$ forest tomography (DESI, Subaru PFS). If SMBHs are high-connectivity nodes of the null-space network, their angular two-point correlation should show excess clustering at scales between the virial radius and the Hubble horizon.

**Prediction 8: CMB polarization vortex statistics.** The CMB polarization field ($Q + iU$ Stokes parameters) is a complex scalar field with phase singularities. Anomalous clustering at scales corresponding to the ER bridge connectivity length would be testable with Simons Observatory and CMB-S4 polarization maps.

---

## IX. Summary

| Structure | Wave Physics | Gravitational Physics | Null-Space Network |
|---|---|---|---|
| Null point | $\psi = 0$, $\arg(\psi)$ undefined | $\xi_\mu \xi^\mu = 0$ at event horizon | Node in the ER bridge graph |
| Topological charge $q$ | Phase winding $\pm 1$ | BH mass, spin, charge | Conserved network quantum number |
| Pair creation | Nulls appear in $+/-$ pairs | BH formation from collapse | New ER bridge established |
| Pair annihilation | Opposite-charge nulls merge | BH merger, ringdown | ER bridge merges, complexity grows |
| Superluminal motion | Berry $v \to \infty$ near annihilation | Merger waveform peak strain | Non-traversable superluminal null-point dynamics |
| Markov blanket | Nearest-neighbor null points | Event horizon (no-hair theorem) | Holographic boundary screening interior |
| col$(F)$ | Measurable phase gradient directions | Observable BH parameters ($M, J, Q$) | External degrees of freedom |
| ker$(F)$ | Unmeasurable interior topology | Behind-horizon interior | Entanglement-mediated, not directly observable |
| Charge conservation | $\sum q_i = 0$ in compact regions | Area theorem $\delta A \geq 0$ | Total entanglement entropy non-decreasing |
| Dark matter | — | NFW: $\rho \propto r^{-1}$ to $r^{-3}$ | $\rho_{\text{DM}} \propto \nabla^2 S_{\text{EE}}(r)$ |
| Connectivity | — | Cosmic web, SMBH distribution | ER = EPR: entanglement = spatial connectivity |

---

## References

Berry, M. V. "Disruption of Wavefronts: Statistics of Dislocations in Incoherent Gaussian Random Waves." *J. Phys. A: Math. Gen.* 11, 27–37, 1978.

Carter, B. "Global Structure of the Kerr Family of Gravitational Fields." *Phys. Rev.* 174, 1559–1571, 1968.

Dong, X. "Holographic Entanglement Entropy for General Higher Derivative Gravity." *JHEP* 01, 044, 2014.

Einstein, A. and Rosen, N. "The Particle Problem in the General Theory of Relativity." *Phys. Rev.* 48, 73–77, 1935.

Einstein, A., Podolsky, B., and Rosen, N. "Can Quantum-Mechanical Description of Physical Reality Be Considered Complete?" *Phys. Rev.* 47, 777–780, 1935.

Engelhardt, N. and Wall, A. C. "Quantum Extremal Surfaces: Holographic Entanglement Entropy Beyond the Classical Regime." *JHEP* 01, 073, 2015.

Friston, K., Da Costa, L., Tschantz, A., et al. "Designing Ecosystems of Intelligence from First Principles." *Collective Intelligence* 3(1), 2024.

Gibbons, G. W. and Hawking, S. W. "Cosmological Event Horizons, Thermodynamics, and Particle Creation." *Phys. Rev. D* 15, 2738, 1977.

Hawking, S. W. "Particle Creation by Black Holes." *Commun. Math. Phys.* 43, 199–220, 1975.

Hawking, S. W. and Ellis, G. F. R. *The Large Scale Structure of Space-Time.* Cambridge University Press, 1973.

Jacobson, T. "Thermodynamics of Spacetime: The Einstein Equation of State." *Phys. Rev. Lett.* 75, 1260–1263, 1995.

Kaminer, I. et al. "Superluminal Correlations in Ensembles of Optical Phase Singularities." *Nature* 651, 920–926, 2026.

Kerr, R. P. "Gravitational Field of a Spinning Mass as an Example of Algebraically Special Metrics." *Phys. Rev. Lett.* 11, 237–238, 1963.

Lelli, F., McGaugh, S. S., and Schombert, J. M. "SPARC: Mass Models for 175 Disk Galaxies with Spitzer Photometry and Accurate Rotation Curves." *AJ* 152, 157, 2016.

Maldacena, J. "The Large $N$ Limit of Superconformal Field Theories and Supergravity." *Adv. Theor. Math. Phys.* 2, 231–252, 1998.

Maldacena, J. and Susskind, L. "Cool Horizons for Entangled Black Holes." *Fortschritte der Physik* 61(9), 781–811, 2013.

Maldacena, J., Shenker, S. H., and Stanford, D. "A Bound on Chaos." *JHEP* 08, 106, 2016.

Milgrom, M. "A Modification of the Newtonian Dynamics as a Possible Alternative to the Hidden Mass Hypothesis." *ApJ* 270, 365–370, 1983.

Navarro, J. F., Frenk, C. S., and White, S. D. M. "The Structure of Cold Dark Matter Halos." *Astrophys. J.* 462, 563–575, 1996.

Nye, J. F. and Berry, M. V. "Dislocations in Wave Trains." *Proc. Roy. Soc. Lond. A* 336, 165–190, 1974.

Penrose, R. "Gravitational Collapse and Space-Time Singularities." *Phys. Rev. Lett.* 14, 57–59, 1965.

Ramstead, M. J. D. et al. "On Bayesian Mechanics: A Physics of and by Beliefs." *Interface Focus* 13(3), 20220029, 2023.

Ryu, S. and Takayanagi, T. "Holographic Derivation of Entanglement Entropy from AdS/CFT." *Phys. Rev. Lett.* 96, 181602, 2006.

Sekino, Y. and Susskind, L. "Fast Scramblers." *JHEP* 10, 065, 2008.

Susskind, L. "The World as a Hologram." *J. Math. Phys.* 36, 6377–6396, 1995.

Susskind, L. "Computational Complexity and Black Hole Horizons." *Fortschritte der Physik* 64, 24–43, 2016.

Van Raamsdonk, M. "Building Up Spacetime with Quantum Entanglement." *Gen. Rel. Grav.* 42, 2323–2329, 2010.

Verlinde, E. "On the Origin of Gravity and the Laws of Newton." *JHEP* 04, 029, 2011.

Verlinde, E. "Emergent Gravity and the Dark Universe." *SciPost Phys.* 2, 016, 2017.

---

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · April 2026
