# Notation

Quick lookup for symbols. Full formula walkthroughs: **[FORMULAS.md](FORMULAS.md)**.

## Logical and set symbols

| Symbol | Read as | Meaning in this framework |
|--------|---------|---------------------------|
| $\forall$ | for all | Universal quantifier over structures, nodes, or times. |
| $\exists$ | there exists | At least one object with a property. |
| $\iff$ | if and only if | Both directions hold; definitions often use this. |
| $\equiv$ | identical to / defined equal | Same object or same value by definition. |
| $\nvdash$ | does not prove | In formal system $S$, no proof of … |
| $\bot$ | bottom / absurdity | Contradiction; false in all models. |
| $\models$ | satisfies / is a model of | State $x$ obeys rules of structure $S$. |
| $\in$ | element of | Membership in a set or structure. |
| $\subseteq$ | subset | Contained in (possibly equal). |
| $\setminus$ | set minus | Remove elements of second set from first. |
| $\cap$ | intersection | Objects obeying both structures (R06). |
| $\emptyset$ | empty set | No observer coupling (FS03). |
| $\perp$ | independent | No statistical influence (AS02). |

## Structures and reality

| Symbol | Meaning |
|--------|---------|
| $S$, $S_i$ | A candidate **structure** (universe spec); $i$ indexes universes. |
| $S_A$, $S_B$ | Two parallel structures for overlap (R06). |
| $\text{Exists}(S)$ | $S$ is **realized** in the multiverse. |
| $\text{Consistent}(S)$ | $S$ is logically consistent ($S \nvdash \bot$). |
| $\mathcal{M}$ | Set of all consistent structures; the multiverse. |
| $\mathcal{R}_{total}$ | Total reality; **defined** as $\mathcal{M}$ (A02). |
| $\Omega_{overlap}$ | $S_A \cap S_B$; shared domain where both rule sets apply. |
| $\text{Rules}(S)$ | Rule set / laws encoded in structure $S$. |

## Consciousness and experience

| Symbol | Meaning |
|--------|---------|
| $\mathcal{C}(S)$ | Scalar summary: “has consciousness” when $> 0$ (A03). |
| $\mathcal{C}_n$ | Conscious structure of node $n$ (R08). |
| $\mathbf{M}(S)$, $\mathbf{M}(f(t))$ | **Self-model** of structure or subsystem $f$. |
| $\Phi(S)$ | Integrated information between $S$ and $\mathbf{M}(S)$. |
| $\mathbf{I}(A; B)$ | **Mutual information** between $A$ and $B$. |
| $n$ | Experiencing **node** (agent) inside $S_i$. |
| $\text{Reality}_{local}(n)$ | Normalized “full reality” from the inside (A04; fixed to 1). |
| $\text{PerceivedExperience}(n)$ | Phenomenology placeholder for $n$. |
| $\text{LocalPhysics}(S_i)$ | Dynamics and laws **inside** $S_i$. |

## Memory sets (AS02)

| Symbol | Meaning |
|--------|---------|
| $\mathcal{M}_{Total}$ | All memories (full knowledge), including prior lives if any. |
| $\mathcal{M}_{Primary}$ | Withheld partition: $\supseteq \mathcal{M}_{\text{origin}} \cup \mathcal{M}_{\text{prior-lives}} \cup \mathcal{M}_{\text{meta}}$. |
| $\mathcal{M}_{\text{prior-lives}}$ | Recall of **previous sessions / past lives** (subset of primary). |
| $\mathcal{M}_{\text{origin}}$ | Base-layer or pre-embodiment identity (subset of primary). |
| $\mathcal{M}_{\text{meta}}$ | Sim/test status, immortality, post-death outcomes (subset of primary). |
| $\mathcal{M}_{Active}(t)$ | $\mathcal{M}_{Total} \setminus \mathcal{M}_{Primary}$ during $[t_{birth}, t_{death}]$ — **why this life lacks past-life memory**. |

## Quantum-style symbols (features FS01, FS03)

| Symbol | Meaning |
|--------|---------|
| $\vert{}\psi\rangle$, $\vert{}\Psi\rangle$ | State vector (pure state). |
| $\rho$ | **Density matrix** (possibly mixed state). |
| $\otimes$ | Tensor product of subsystems. |
| $c_k$ | Amplitude of branch $k$ in a superposition. |
| $\vert{}c_k\vert{}^2$ | Probability of outcome $k$ (Born rule). |
| $\hat{O}_{observer}$ | Observer / interaction operator on environment. |
| $E_{PR}$ | EPR non-local correlation (reference). |

## Dynamics, law blends, thermodynamics

| Symbol | Meaning |
|--------|---------|
| $f(t)$ | State of self-referential subsystem at time $t$. |
| $g(\cdot,\cdot)$ | Update map in consciousness loop (A03). |
| $L_A$, $L_B$, $L_{local}$ | Law functionals on state $x$ (R06). |
| $\alpha$ | Blend weight in $[0,1]$ on overlap ($1$ = pure $A$). |
| $S_{entropy}$ | Entropy (thermodynamic or metaphorical). |
| $H_{cognitive}$ | Cognitive entropy of base entity (R09). |
| $\Delta H_{rejuvenation}$ | Entropy drop after sim experience. |

## Evaluation and teleology

| Symbol | Meaning |
|--------|---------|
| $\mathbf{EthicalChoice}(t)$ | Moral choice signal at $t$ (Q01). |
| $w(t)$ | Time weight in ethical integral. |
| $\text{Evaluate}(Entity)$ | Lifetime score (integral). |
| $\Theta_{threshold}$ | Pass threshold (constant). |
| $\text{Vulnerability}(t)$ | Exposure to finitude/risk (R09). |
| $\Delta \text{Empathy}$ | Empathy gain (proportional to integrated vulnerability). |

## Named constants (you choose per universe)

| Constant | Typical use |
|----------|-------------|
| $\Phi_{critical}$ | Minimum $\Phi$ for subject status (A03). |
| $T_{max}$ | Maximum lifespan $\Delta t_{lifespan}$ (AS03). |
| $t_{birth}$, $t_{death}$ | Session window (AS02, Q01). |
| $\Theta_{threshold}$ | Pass/fail on $\text{Evaluate}$ (Q01). |
| $\alpha$ or $\alpha(x,t)$ | Overlap law mix (R06). |

See [universe.schema.yaml](universe.schema.yaml) and [examples/earth-session.yaml](examples/earth-session.yaml).

## Time and probability

| Symbol | Meaning |
|--------|---------|
| $t$, $T$ | Continuous time or session length. |
| $[t_{birth}, t_{death}]$ | Closed interval of the life-session. |
| $\mathbb{P}(\cdot \mid \cdot)$ | Conditional probability. |
| $\propto$ | Proportional to (unknown positive scale factor). |
| $\longrightarrow$ | Informal “leads to / correlates with” (FS01 sketch only). |
