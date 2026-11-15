# The-Four-States-of-Entropy-Reconciling-the-Farid-Descriptive-Framework-with-Mainstream-Physics
The Four States of Entropy:
Reconciling the Farid Descriptive Framework
with Mainstream Physics
Version 3.0 — Revised, Expanded, and Verified
Prof. Dr. Md. Faridul Islam Chowdhury
Tanfarid Vision Research Institute, Bogura, Bangladesh
ORCID: 0000-0003-3178-0671
November 2026
Abstract
The “Farid descriptive framework” assigns four accessible names to four entropy-flow sit-
uations: positive, negative, balance, and imbalance. The names are pedagogical — plain-
language labels for four well-known situations in mainstream physics. This note shows how
the four names map exactly onto the mainstream entropy-balance equation; separates the
“balance” label into two physically distinct situations (thermodynamic equilibrium and the
non-equilibrium steady state, NESS); gives a formal criterion and a numerically verified
example for each class; and connects the same structure at the stochastic level to the mono-
tonic decay of the Kullback–Leibler relative entropy and to Landauer’s principle. No new
claim about mainstream physics is made; FQCU-specific predictions are discussed elsewhere
in the companion manuscript.
1 Mainstream definitions and the entropy-balance equation
1.1 Definitions of entropy
In modern physics, the entropy S admits two equivalent expressions:
• Boltzmann:
S = kB ln Ω, (1)
where Ω is the number of microstates compatible with a given macrostate.
• Gibbs–Shannon:
S = −kB
∑
i
pi ln pi, (2)
where pi is the probability of microstate i.
1.2 Entropy balance for an open system
For any system, the standard entropy-balance equation (Kondepudi–Prigogine [2], Seifert [3])
reads dSsys
dt = −ΦS (t) + ΣS (t), ΣS (t) ≥ 0, (3)
where Ssys is the system’s total entropy, ΦS ≥ 0 is the rate of entropy export to the environment,
and ΣS ≥ 0 is the internal entropy-production rate — non-negative by the second law. Locally,
∂s(x, t)
∂t = −∇·Js(x, t) + σ(x, t), σ ≥ 0. (4)
1
1.3 Total entropy change
For system plus environment,
∆Stot = ∆Ssys + ∆Senv ≥ 0, (5)
with equality only for reversible processes. This is the second law — not ∆Ssys ≥ 0. This
distinction underlies every class below.
2 The four states — formal criteria, examples, numbers
2.1 Positive entropy (∆Ssys > 0)
Criterion: ΣS > ΦS . Internal production exceeds export, so dSsys/dt > 0.
Examples and numbers (verified):
• Ice melting to water: ∆Sfusion = Lf /Tm = (333.55 kJ/kg)/(273.15 K) ≈ 1.221 kJ/(K · kg)
— melting 1 kg of ice raises the system entropy by +1.221 kJ/K.
• Water to steam: ∆Svap = Lv/Tb = (2256.4 kJ/kg)/(373.15 K) ≈ 6.047 kJ/(K · kg).
• Free expansion, mixing, finite-rate heat transfer — all irreversible, ∆Stot > 0.
2.2 Negative entropy, or negentropy (∆Ssys < 0)
Criterion: 0 ≤ ΣS < ΦS . The system’s entropy decreases — but only by exporting entropy to
the environment, which gains at least ΦS − ΣS , so that ∆Stot > 0 always.
Schrödinger (What is Life?, 1944 [1]) named this “negentropy”: a living organism maintains
its low-entropy state by absorbing “negative entropy” from its surroundings.
Examples and numbers:
• Water freezing: ∆Ssys = −1.221 kJ/(K · kg); the environment gains at least as much —
the warm coil at the back of a refrigerator is the visible bill for this transaction.
• Star formation: a gas cloud contracts; its local entropy drops while radiation carries entropy
away.
• Cell growth: an organism keeps its local entropy low at the price of producing entropy in
its environment.
Caution: this does not violate the second law, which states ∆Stot ≥ 0 — not ∆Ssys ≥ 0.
2.3 Balance entropy — two physically distinct situations
Essential correction: the “balance” label covers two completely different physical situations,
which mainstream physics keeps separate.
(a) Thermodynamic equilibrium:
ΣS = 0, ΦS = 0. (6)
No flows, no entropy production; total entropy is maximal; detailed balance holds. Example:
thermal equilibrium inside a closed adiabatic container.
(b) Non-equilibrium steady state (NESS):
0 < ΣS = ΦS . (7)
2
Entropy is produced inside and exported at the same rate; Ssys stays constant. The system
looks static but is actively flowing.
Prigogine’s minimum entropy production theorem (1945; Nobel 1977 [2, 4]): in a
linear NESS, for prescribed thermodynamic forces, the total entropy-production rate ΣS is
minimized. This is why a NESS is stable — small perturbations relax back to the local minimum
of production.
NESS examples and numbers (verified):
• Human body (homeostasis): basal metabolic output ∼ 100 W at T ≈ 310 K, so ΣS ∼
100/310 ≈ 0.32 W/K.
• Sun (main sequence): L⊙ = 3.83 × 1026 W, T⊙ ≈ 5778 K, so ΦS ≈ L⊙/T⊙ ≈ 6.6 × 1022
W/K. The vast entropy created by fusion in the core is radiated away at exactly this rate
— which is why the Sun remains steady for billions of years.
• Earth’s climate: with absorbed solar power ∼ 240 W/m2, ΣS ≈ 240 ( 1
255 − 1
5778
) × 4πR2
⊕ ≈
5 × 1014 W/K (order 1014–1015 W/K). Low-entropy sunlight enters, high-entropy infrared
leaves — this difference drives the terrestrial climate engine.
2.4 Imbalance entropy (∆Ssys̸ = 0)
Criterion: a large thermodynamic gradient (∇T , ∇μ, or ∇P large), hence large local σ and
rapid dSsys/dt.
This label overlaps classes (2.1) and (2.2); it is retained because it makes the driving gradient
explicit.
Examples and numbers:
• Atmospheric convection: the equator-to-pole temperature contrast ∼ 30–40 K drives cy-
clones and anticyclones.
• Supernova: core collapse releases ∼ 1046 J of gravitational binding energy, creating an
enormous entropy gradient.
• Black-hole accretion: the Bekenstein–Hawking entropy SBH = kBA/(4ℓ2
P) [6, 7]; for a solar-
mass black hole, SBH /kB ≈ 1.05 × 1077 — incomparably larger than the progenitor star’s
entropy: the extreme case of entropy growth in gravitational collapse.
3 Microscopic connections: the H-theorem and Landauer’s prin-
ciple
The four states above are macroscopic. At the stochastic level the same structure appears in
two standard results, which are also the basis of the entropy chapter of the companion FQCU
manuscript:
(a) Monotonic decay of the relative entropy. For a system coupled to a thermal bath,
the Kullback–Leibler divergence from the equilibrium distribution Peq obeys
d
dt DKL(Pt ∥ Peq) ≤ 0, F [Pt] − Feq = kBT DKL(Pt ∥ Peq) ≥ 0 (8)
— the microscopic form of the entropy balance (the H-theorem) [3]. In “balance (a)” one has
DKL = 0; in the “positive” state the system’s own S grows along the decay of DKL; a NESS
carries a steady, nonzero production.
(b) Landauer’s principle. Erasing one bit of information dumps at least kBT ln 2 of heat
into the environment [8] — information processing is not exempt from the entropy balance.
This is the informational form of the “negative” state: local informational order is bought at
an environmental price.
3
4 Summary table
Table 1: The four Farid labels, their mainstream counterparts, formal criteria, and verified
examples.
Farid label Mainstream name Criterion ∆Stot Example
Positive Positive entropy ΣS > ΦS > 0 Ice melting (+1.221
kJ/K·kg)
Negative Negentropy 0 ≤ ΣS < ΦS > 0 Water freezing (−1.221
kJ/K·kg); living
organisms
Balance (a) Thermodynamic equilib-
rium
ΣS = ΦS = 0 = 0 (maxi-
mal)
Closed adiabatic
container
Balance (b) Non-equilibrium steady
state (NESS)
0 < ΣS = ΦS > 0 Sun (6.6 × 1022 W/K);
human body (0.32
W/K)
Imbalance Non-equilibrium gradient large ∇ ln T > 0 Supernova; black hole
(SBH ∼ 1077kB)
5 What the Farid framework adds — and what it does not
5.1 What it adds
• An accessible taxonomy: four plain-language labels that make thermodynamics ap-
proachable for first-year students and general readers.
• A common frame for life and stars: organisms and stars are both NESS systems
(local negentropy inside a global steady state) — this insight is the framework’s pedagogical
strength.
• Reconciliation with clarity: four names that keep their link to mainstream physics
explicit.
5.2 What it does not add
• No new entropy law: all four states fall within the mainstream balance equation (3).
• The equilibrium/NESS split is not the framework’s own — it is Prigogine’s 1945 work [4].
• No independent numerical prediction: every number above is standard reference data
(recomputed and verified for this version).
• No FQCU-specific signature: these labels supply no experimental prediction of FQCU.
5.3 Relation to the mainstream
Every term of the Farid framework is sharply defined in mainstream physics. The “Farid
descriptive framework” is therefore a pedagogical frame, not a new theory. This explicitness is
consistent with the overall honesty policy of the FQCU programme: where no new claim exists,
no new claim is made.
4
References
[1] E. Schrödinger, What is Life? (Cambridge University Press, 1944).
[2] D. Kondepudi and I. Prigogine, Modern Thermodynamics: From Heat Engines to Dissipative
Structures, 2nd ed. (Wiley, 2014).
[3] U. Seifert, “Stochastic thermodynamics, fluctuation theorems and molecular machines,”
Rep. Prog. Phys. 75, 126001 (2012).
[4] I. Prigogine, Étude thermodynamique des phénomènes irréversibles (Dunod, 1947).
[5] C. Van den Broeck and M. Esposito, “Ensemble and trajectory thermodynamics: A brief
introduction,” Physica A 418, 6–16 (2015).
[6] J. D. Bekenstein, “Black holes and entropy,” Phys. Rev. D 7, 2333 (1973).
[7] S. W. Hawking, “Particle creation by black holes,” Commun. Math. Phys. 43, 199 (1975).
[8] R. Landauer, “Irreversibility and heat generation in the computing process,” IBM J. Res.
Dev. 5, 183 (1961).
A The two points at which the original description was cor-
rected
Original description Corrected form Reason
“Balance entropy: ∆Snet = 0”
(single class)
Two distinct classes: (a) equilibrium
(ΣS = ΦS = 0), (b) NESS (ΣS =
ΦS > 0)
The second law keeps produc-
tion off in equilibrium; in a
NESS entropy is actively pro-
duced and exported — differ-
ent physical situations
“Negative entropy … but the
environment’s total entropy in-
creases” (one sentence)
Formal criterion ΣS < ΦS and
∆Stot = ∆Ssys + ∆Senv ≥ 0
The second law is not
∆Ssys ≥ 0; a formal state-
ment is required
Version note: added/changed in version 3.0 — (i) all numerical values recomputed and verified
(Earth’s climatic entropy production ≈ 5 × 1014 W/K from the standard absorbed-flux estimate
of 240 W/m2); (ii) a new microscopic-connections section: DKL decay and Landauer’s principle
(§3); (iii) the solar-mass black-hole value fixed at 1.05 × 1077; (iv) layout and bibliography.
5
